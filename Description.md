# Payment Management App

## Overview
The Payment Management App is a PowerApps solution designed to streamline payment management and approval processes within an organization. It integrates with Excel and SharePoint for data storage and leverages automated email notifications for payment approvals and alerts. Additionally, the app allows users to upload POs and invoices for enhanced visibility and document management.

---

## Features
- **Dynamic Form**: Capture key payment details, including:
  - PO Number
  - Payment Percentage
  - Client Email Address
  - Approval Status (e.g., tick/cross for advance payment required)
- **Document Uploads**:
  - Upload POs and invoices as supporting documents to SharePoint using Power Automate for better visibility.
- **Automated Email Notifications**:
  - Notify relevant parties of payment status and details.
  - Emails include key information such as payment percentage and status.
- **Data Storage**:
  - Submit payment data to both Excel and a SharePoint Document Library.
- **Conditional Logic**:
  - If advance payment is required, specific fields like payment percentage are mandatory.
- **Unique Tracking Codes**:
  - Generate unique ddmmyy-hhmmss tracking codes for each payment entry.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **Microsoft Power Automate**:
  - Automated email alerts and document uploads
- **Excel**:
  - Data storage and tracking
- **SharePoint**:
  - Backend for document and payment data storage
- **Office 365 Outlook Integration**:
  - Email functionality

---

## How It Works
1. **Submit Payment Data**:
   - Users enter payment details into the PowerApps form.
   - Data is stored in an Excel file and uploaded to a SharePoint Document Library.
2. **Document Uploads**:
   - Users can upload supporting documents (POs and invoices), which are stored in SharePoint using Power Automate flows.
3. **Automated Emails**:
   - An email is sent to the client and a fixed recipient upon submission.
   - If advance payment is required, an additional email is sent to the approver with the selected payment percentage.
4. **Unique Tracking**:
   - A unique tracking code is generated for each payment request, ensuring traceability.

---

## Benefits
- Simplifies payment management with centralized data storage.
- Automates email notifications to reduce manual follow-ups.
- Enhances document visibility by allowing POs and invoices to be uploaded.
- Ensures data integrity with mandatory fields and unique tracking codes.

---

## Future Enhancements
- Integration with Power BI for payment insights and reporting.
- Multi-currency support.
- Role-based access for enhanced security.

---

