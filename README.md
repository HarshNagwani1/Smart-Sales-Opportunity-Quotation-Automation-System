 


# Smart Sales Opportunity & Quotation Automation System 
 
## 🚀 Overview 
This project automates the **sales quotation process** in Salesforce using **Flows, Approval Processes, PDF generation, and Email automation**.   
It is built as part of the **TCS iON/LastMile Salesforce program** to showcase advanced Salesforce CRM automation capabilities. 
 
--- 
 
## 🎯 Features 
- **Custom Object: Quotation__c** 
  - Fields: Quotation Name, Total Amount, Status, Valid Till, Opportunity Lookup 
- **Automation with Flows** 
  - Automatically creates a Quotation when an Opportunity is moved to **Closed Won** 
- **Approval Process** 
  - Multi-step approval workflow for Quotations 
  - Status transitions: `Draft → Sent → Approved/Rejected` 
- **PDF Generation** 
  - Professional invoice-style PDF document generated from Quotation details 
  - Download button on record page: *Generate PDF* 
- **Email Automation** 
  - Auto-email notifications on Approval/Rejection of Quotations 
- **Reports & Dashboards** 
  - Quotations by Status (Draft, Sent, Approved, Rejected) 
  - Visual dashboard for business insights 
 
--- 
 
## 🛠️ Tech Stack 
- **Salesforce Platform** 
  - Custom Objects, Fields, Flows 
  - Approval Processes 
  - Visualforce Pages (PDF generation) 
- **GitHub** (Version Control) 
- **Documentation** with screenshots and diagrams 
 
--- 
 
## 📂 Project Structure 
  

smart-salesforce-quotation-automation/ 

 │ 

 ├── force-app/ # Salesforce Metadata 

 │ ├── main/default/objects/ # Custom Objects & Fields 

 │ ├── main/default/flows/ # Automation Flows 

 │ └── main/default/pages/ # Visualforce Pages (PDF) 

 │ 

 ├── docs/ # Documentation & Screenshots 

 │ ├── architecture.png 

 │ └── approval-process.png 

 │ 

 ├── scripts/ # Apex/Soql scripts for testing 

 │ 

 ├── README.md # Project Overview 

 └── Smart_Sales_Project.docx # Detailed Phase-wise Documentation 

 
--- 
 
## ⚙️ Installation & Setup 
1. **Clone the Repo** 
   ```bash 
   git clone https://github.com/HarshNagwani1/Smart-Sales-Opportunity-Quotation-Automation-System.git 
   cd Smart-Sales-Opportunity-Quotation-Automation-System 
  

Authorize Salesforce Org 

sf org login web --set-default --alias myorg 
  

Deploy Metadata 

sf project deploy start --source-dir force-app 
  

Open Org 

sf org open 
  

 

🧪 Usage 

Create an Opportunity and set Stage = Closed Won 

System will auto-create a Quotation (Draft) 

Submit Quotation for Approval 

Approver can Approve/Reject, status auto-updates 

Click Generate PDF to download professional Quotation PDF 

Email notifications will be sent automatically 


👨‍💻 Author 

Harsh Nagwani 

 TCS iON/LastMile Salesforce Program | AIML Enthusiast 

 
