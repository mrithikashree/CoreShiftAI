\# Royal Bhavana Rice Company

\# Google Form Specification



\---



\# Purpose



This document defines the structure, validation rules, and integration requirements for the customer enquiry form.



The form will capture leads from the website and automatically store them in Google Sheets.



\---



\# Form Information



Form Name



Royal Bhavana Rice Company – Product Enquiry



\---



\# Form Sections



\## Section 1 – Customer Information



\### Full Name



Type



Short Answer



Required



Yes



Validation



Minimum 3 characters



\---



\### Mobile Number



Type



Short Answer



Required



Yes



Validation



10-digit mobile number



\---



\### Email Address



Type



Short Answer



Required



No



Validation



Valid email format



\---



\### City



Type



Short Answer



Required



Yes



\---



\### State



Type



Dropdown



Required



Yes



Default



Karnataka



(Add more states later)



\---



\# Section 2 – Product Interest



\### Product Interested



Type



Dropdown



Required



Yes



Values



\- Dia Rice

\- Premium Rice

\- Other Products



\---



\### Quantity Required



Type



Dropdown



Required



No



Values



\- Less than 5 kg

\- 5–10 kg

\- 10–25 kg

\- More than 25 kg



\---



\### Customer Type



Type



Dropdown



Required



Yes



Values



\- Home Customer

\- Retail Shop

\- Distributor

\- Wholesale Buyer



\---



\# Section 3 – Additional Details



\### Message



Type



Paragraph



Required



No



Placeholder



Tell us about your requirement.



\---



\# Consent



Checkbox



Required



Yes



Text



I agree to be contacted regarding my enquiry.



\---



\# Submission Settings



After submission



Display:



"Thank you for contacting Royal Bhavana Rice Company. Our team will contact you shortly."



\---



\# Google Sheet Integration



Every submission should create one new row.



Columns:



\- Timestamp

\- Lead ID

\- Name

\- Mobile

\- Email

\- City

\- State

\- Product

\- Quantity

\- Customer Type

\- Message

\- Lead Source

\- Status



\---



\# Default Values



Lead Source



Website



Status



New



Priority



Pending (updated later in CRM)



\---



\# Validation Rules



\- Required fields must not be empty.

\- Mobile number must contain exactly 10 digits.

\- Email should be validated if provided.

\- Consent must be accepted before submission.



\---



\# Future Enhancements



Phase 2



\- File Upload

\- Product Images

\- WhatsApp Notification



Phase 3



\- OTP Verification

\- AI Lead Qualification

\- Auto Language Detection



\---



End of Document

