# 🤖 GP Team – Discord AI Assistant  
Official AI assistant system built for GP Team using Discord.py + Google AI (Gemini).  
This bot provides a fully controlled, safe, and structured AI chat system with AutoMod, channel restrictions, cooldowns, and GP Team internal knowledge.

---

## 📌 Features  
### 🔹 **1. GP Team AI Chat System**
- Responds using official GP Team knowledge rules.
- Always follows formatting, tone, and style guidelines.
- Supports conversation history per-user, per-channel.
- Smart system prompt + short/compact responses by default.
- Auto language detection (Arabic / English).

### 🔹 **2. AutoMod (AI Moderation)**
- Uses an AI moderation model to analyze messages.
- Detects:
  - insults  
  - hate speech  
  - NSFW  
  - violence  
  - harassment  
- High-severity violations → automatic 15-minute timeout.
- Low severity → sends a warning message.
- Exempt roles system (to skip moderation for staff).

### 🔹 **3. Channel-Locked AI**
- The AI only replies in a specific channel set by `/setchannel`.
- Prevents spam and restricts assistant responses.

### 🔹 **4. Cooldown System**
- 5 second cooldown per user.
- Prevents spam and message flooding.

### 🔹 **5. Slash Commands**
#### `/chat <message>`
Send a question directly to the AI inside the assigned channel.

#### `/setchannel <#channel>`
Admins-only — sets the official AI channel.

#### `/resetchat`
Clears a user's chat history with the AI in that channel.

---

## 📂 Project Structure  
