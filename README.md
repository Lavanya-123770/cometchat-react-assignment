# CometChat Internship Assignment – React UI Kit Integration

This project is part of the CometChat Internship evaluation.  
It demonstrates the integration of the **CometChat React UI Kit** using the **UI Kit Builder**, customization, and evaluation of product experience.

---

## 🚀 Features Implemented

### ✔ Login Screen  
- Sample users (Andrew Joseph, George Alan, Nancy Grace, etc.)  
- UID-based login  
- Smooth authentication experience  

### ✔ Chats Module  
- One-on-one chats  
- Group conversations  
- Typing indicators (when supported)  
- Read receipts, delivery states  
- Message reactions, attachments, emojis  

### ✔ UI Kit Builder Export  
The UI was fully designed & customized in the **CometChat UI Kit Builder**, exported as a React project, and integrated locally.

---

## 📸 Screenshots  
(Add your screenshots below)

- Login Screen  
- Chat Window  
- Groups View  
- Calls Tab  
- Users Tab  
- UI Kit Builder Theme Editor  

---

# 🔍 Findings & Issues Identified

## 1️⃣ Dashboard Findings & Observations

1. **User creation flow is not intuitive**  
   Difference between "Authentication" vs "User Management" is not clearly explained.

2. **API keys visibility is high**  
   Dashboard exposes App ID & Region without strong guidance on securing credentials.

3. **Scattered navigation**  
   Features like Chats, Calls, Moderation, Logs, and Settings are separated, making discovery slower.

4. **Missing onboarding tutorial**  
   A step-by-step guide for first-time developers would significantly improve usability.

---

## 2️⃣ UI Kit Builder Findings & Limitations

1. **Tooltip Error (“Tooltip failed to load”)**  
   Occurs occasionally when hovering certain icons.

2. **Customization depth is limited**  
   Allows color & typography changes but lacks deep UI component customization (e.g., bubble shapes, spacing).

3. **No per-component live preview**  
   All theme changes apply globally; individual previews would help.

4. **Must re-export after every change**  
   No auto-sync with an existing project; re-export required for any update.

5. **No way to preview group metadata**  
   Group description and member preview not shown inside UI Kit Builder.

---

## 3️⃣ Documentation Findings

1. **Multiple integration options can confuse beginners**  
   UI Kit, SDK, & Component Kit docs appear together without a clear onboarding path.

2. **Advanced feature documentation is shallow**  
   - Moderation  
   - Push Notifications  
   - Webhooks  
   These topics need more real-world examples.

3. **Limited theming examples**  
   Only basic colors & typography demonstrated; deep theme override examples missing.

4. **No clear mention on where to paste credentials in exported UI Kit**  
   Beginners must explore project structure manually.

---

## 4️⃣ Implementation Findings (Local Testing)

1. **Empty chat window shows no placeholder**  
   Should display something like: “Start your conversation…”

2. **Typing indicator not always visible**  
   Appears inconsistently in exported UI Kit.

3. **Message reaction popup loads slowly**  
   Minor delay before showing reactions.

4. **Message read/delivered icons not obvious**  
   Could benefit from tooltips or clearer icons.

5. **Online/offline presence indicator is not prominent**  
   Hard to identify user status at a glance.

6. **Invalid UID login shows no proper error message**  
   UI simply refreshes; should display an error alert.

---

# 🛠️ Installation & Running the Project

### Install dependencies
```bash
npm install
