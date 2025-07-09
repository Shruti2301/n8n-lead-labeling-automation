
# 🧠 n8n Lead Labeling Automation
I Automated My Lead Inbox with n8n — and It Now Sorts Itself! 
[Image1.jpg]

This project is a no-code automation built with [n8n](https://n8n.io) that:
- Automatically sends email notifications on form submission
- Classifies leads based on their budget
- Applies Gmail labels (Low, Medium, High)

## 🔧 Workflow Components
- **Trigger**: Form submission
- **Logic**: Switch node to check budget ranges
- **Action**: Send custom emails + add Gmail labels

## 🖼️ Screenshots
See the `/screenshots` folder for full examples of the workflow and Gmail inbox.

## 📥 How to Use
1. Import `workflow.json` into your n8n instance
2. Configure Gmail credentials and label names
3. Connect to your form data (Webhook or Google Form)

## 📫 Contact
Built by Shruti Mandaokar (https://www.linkedin.com/in/shruti-mandaokar/)
