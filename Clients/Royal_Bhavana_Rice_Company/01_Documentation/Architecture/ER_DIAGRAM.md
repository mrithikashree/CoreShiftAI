\# Royal Bhavana Rice Company

\# Entity Relationship Diagram (ERD)



\---



\# Purpose



This document defines the logical database structure for the Royal Bhavana Rice Company Lead Management Platform.



The database is designed using normalized relational principles to support future migration from Google Sheets to Supabase PostgreSQL.



\---



\# Core Entities



\## Lead Master



Stores every customer enquiry.



Primary Key



Lead\_ID



\---



\## Customer Master



Stores unique customer information.



Primary Key



Customer\_ID



Relationship



One Customer



↓



Many Leads



\---



\## Product Master



Stores all RBRC products.



Primary Key



Product\_ID



Relationship



One Product



↓



Many Leads



\---



\## Lead Source Master



Stores lead origin.



Examples



Facebook



Instagram



Google



WhatsApp



QR Code



Website



Amazon



JioMart



Blinkit



Zepto



Swiggy Instamart



\---



\## Lead Status Master



Possible values



New



Hot



Warm



Cold



Converted



Lost



Closed



\---



\## Customer Type Master



Examples



Retail Customer



Wholesale Dealer



Distributor



Supermarket



Hospital



Restaurant



Other



\---



\## Follow-up Master



Stores every follow-up activity.



Relationship



One Lead



↓



Many Follow-ups



\---



\## Activity Log



Stores system activities.



Examples



Lead Created



Lead Updated



Status Changed



Follow-up Completed



Order Generated



\---



\# Entity Relationships



Customer



│



├────< Lead >──── Product



│



├────< Lead Source



│



├────< Lead Status



│



└────< Follow-up



↓



Activity Log



\---



\# Future Entities



Employee Master



Order Master



Invoice Master



Delivery Tracking



Payment History



Notification Log



\---



\# Database Philosophy



One Customer



↓



Multiple Leads



↓



Multiple Follow-ups



↓



One Conversion



↓



One Customer Journey

