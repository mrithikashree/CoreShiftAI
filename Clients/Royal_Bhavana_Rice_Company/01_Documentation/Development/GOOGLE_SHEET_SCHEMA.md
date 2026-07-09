\# Royal Bhavana Rice Company

\# Google Sheet Schema



\---



\# Purpose



This document defines the structure of the Google Sheet used as the Lead Management Database.



The sheet stores all enquiries received from the website and supports reporting, filtering, follow-up, and future CRM integration.



\---



\# Sheet Structure



\## Sheet 1 – Lead Master



| Column | Field Name | Type | Required | Description |

|---------|------------|------|----------|-------------|

| A | Lead ID | Auto | Yes | Unique Lead Number |

| B | Timestamp | Auto | Yes | Form Submission Time |

| C | Customer Name | Text | Yes | Customer Full Name |

| D | Mobile Number | Text | Yes | Customer Contact |

| E | Email | Text | No | Email Address |

| F | City | Text | Yes | Customer City |

| G | State | Text | Yes | Customer State |

| H | Product | Dropdown | Yes | Interested Product |

| I | Quantity | Dropdown | No | Required Quantity |

| J | Customer Type | Dropdown | Yes | Home / Retail / Distributor |

| K | Message | Text | No | Customer Requirement |

| L | Lead Source | Dropdown | Yes | Website, Facebook, Instagram, WhatsApp |

| M | Status | Dropdown | Yes | New, Contacted, Qualified, Converted, Closed |

| N | Priority | Dropdown | Yes | Hot, Warm, Cold |

| O | Assigned To | Text | No | Sales Executive |

| P | Next Follow-up | Date | No | Next Action Date |

| Q | Last Contact Date | Date | No | Last Customer Interaction |

| R | Remarks | Text | No | Sales Notes |

| S | Outcome | Dropdown | No | Converted / Lost |

| T | Lost Reason | Dropdown | No | Price, Competitor, No Response, Others |



\---



\# Dropdown Values



\## Lead Status



\- New

\- Contacted

\- Qualified

\- Follow-up

\- Converted

\- Closed



\---



\## Priority



\- Hot

\- Warm

\- Cold



\---



\## Customer Type



\- Home Customer

\- Retail Shop

\- Distributor

\- Wholesale Buyer



\---



\# Reports Sheet



Display:



\- Total Leads

\- New Leads

\- Contacted Leads

\- Qualified Leads

\- Converted Leads

\- Closed Leads

\- Conversion Rate

\- Lead Source Performance



\---



\# Dashboard Sheet



Widgets:



\- Total Leads

\- Hot Leads

\- Warm Leads

\- Cold Leads

\- Today's Follow-ups

\- Monthly Conversion

\- Lead Source Chart



\---



\# Validation Rules



\- Mandatory fields cannot be blank.

\- Mobile number must contain 10 digits.

\- Dropdown fields should only accept predefined values.

\- Dates should follow DD/MM/YYYY format.



\---



\# Future Enhancements



Phase 2



\- Automatic Lead Assignment

\- Follow-up Reminder

\- WhatsApp Integration



Phase 3



\- AI Lead Scoring

\- Sales Forecasting

\- Predictive Reports



\---



End of Document

