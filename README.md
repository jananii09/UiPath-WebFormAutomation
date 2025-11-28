# UiPath – Web Form Automation Workflow

This repository contains a simple **UiPath workflow** that demonstrates:
- **Opening a web page** in a browser
- **Automatically filling out a contact form** with user data
- **Submitting the form** using UI automation

---

## Project Overview
- Built using **UiPath Studio (Modern Design Experience)**
- Demonstrates usage of **Use Application/Browser**, **Type Into**, and **Click** activities
- A beginner-friendly project to learn **basic web automation** in UiPath

---

## Project Files
- `Main.xaml` → The main automation workflow  
- `project.json` → UiPath project configuration  

---

## Workflow Logic

### 🔹 Use Application/Browser
- Launches the target page:  
  `https://www.selenium.dev/selenium/web/web-form.html`
- Ensures the browser session is managed and closed automatically after the workflow finishes.

### 🔹 Type Into
- Enters sample data:
  - **Name**: `John Doe`
  - **Email**: `john@example.com`
- You can easily replace these hard-coded values with variables or data from Excel.

### 🔹 Click Submit
- Clicks the **Submit** button to send the form.

---

## Example Run
*(Values can be customized as needed)*

| Field | Example Input |
|------|--------------|
| Name | Bala Saravanan K |
| Password | password123 |
| Textarea | Graphic Designer and UI/UX enthusiastic |

---

## Screenshots

<img width="1273" height="687" alt="image" src="https://github.com/user-attachments/assets/92d585f6-4b28-4765-8139-6003a1ac7dd0" />

<img width="1320" height="661" alt="image" src="https://github.com/user-attachments/assets/9b0c84f1-2914-4c66-9bfc-50aedcacb529" />

<img width="1196" height="675" alt="image" src="https://github.com/user-attachments/assets/87e936ae-0234-4dac-96cf-0c01f8cd739b" />

## output

<img width="1228" height="722" alt="image" src="https://github.com/user-attachments/assets/c0285975-b72c-4783-aeaa-676f7d498668" />

---
