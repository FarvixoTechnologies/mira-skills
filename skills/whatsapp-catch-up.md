---
name: whatsapp-catch-up
description: "Summarise unread WhatsApp messages and help reply"
platforms: [phone]
triggers: ["whatsapp e ki esheche", "unread whatsapp", "koi message aaya", "whatsapp check"]
version: 1
updated: 2026-09-24
---

# whatsapp-catch-up

Summarise unread WhatsApp messages and help reply.
1. `phone_action` whatsapp_unread, or `read_notifications` and keep the WhatsApp ones.
2. Summarise by person: "Rina 3 ta, Office group 12 ta". Message text only if asked.
3. To reply, follow the whatsapp-message skill.

If the phone is locked and the lock-screen setting forbids reading, the tool refuses — say so.
