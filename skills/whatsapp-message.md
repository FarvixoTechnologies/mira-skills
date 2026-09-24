---
name: whatsapp-message
description: "Send a WhatsApp message to a contact, read back and confirmed first"
platforms: [phone]
triggers: ["whatsapp e bolo", "whatsapp message", "whatsapp pe bhejo", "whatsapp koro"]
version: 1
updated: 2026-09-24
---

# whatsapp-message

Send a WhatsApp message to a contact, read back and confirmed first.
1. `find_contact` name → number. Several matches? Ask which, by name.
2. Write the message in the user's words; fix only obvious speech-to-text slips.
3. Read it back: "Rina ke likhbo: '…'. Pathabo?" Wait for a clear yes.
4. `whatsapp_message` number, body, confirmed=true. WhatsApp opens with the text typed;
   the user presses send, or, with Accessibility on and after their yes, `read_screen`
   and `tap_on_screen` the send button.

Never: send to a guessed number; change the meaning of the message.
