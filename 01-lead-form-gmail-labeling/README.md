[Lead Form Automation.json](https://github.com/user-attachments/files/21079189/Lead.Form.Automation.json)# 📩 Lead Form Email Labeling Automation (n8n)

## 🧠 About the Project:
This is the very first automation I built using n8n. The goal is to receive lead form submissions from a website or project form, and automatically:

- Send myself an email notification when a new lead comes in
- Label the lead email in Gmail based on the selected budget
  - High Budget → Labeled as “High Budget”
  - Low Budget → Labeled as “Low Budget”

This helps me instantly recognize which leads are premium and act accordingly — even without opening the email.

---

## ⚙️ Tools Used:
- 🧠 n8n (No-Code Automation Platform)
- ✉️ Gmail Node for sending and labeling emails
- 🔄 Switch Node for routing based on project budget

---

## 🔄 How It Works:
1. Trigger node initiates the flow when a new lead is detected.
2. Switch node checks the selected budget value.
3. Depending on the condition:
   - Sends an email to myself
   - Applies a Gmail label based on budget tier

---

## 💡 What I Learned:
- How to use Switch node in n8n
- Conditional logic in workflows
- Gmail API integration for labeling
- Building real-world automation ideas from scratch

---

## 🗂 Workflow File:
Uploaded as lead-form-gmail-labeling.json inside this folder.
[Uploading Lead Form Automation.json…]()

---

## 🖼 Screenshot:
