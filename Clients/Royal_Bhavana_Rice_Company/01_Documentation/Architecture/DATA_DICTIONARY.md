\# Royal Bhavana Rice Company

\# Data Dictionary



\---



\# Purpose



This document defines all business data fields used across the Lead Management Platform.



The same field definitions will be used in:



\- Landing Page

\- Google Form

\- Google Sheets

\- Future Supabase Database

\- CRM Dashboard

\- AI Automation



\---



\# Lead Information



| Field Name | Type | Mandatory | Description |

|------------|------|-----------|-------------|

| Lead ID | Auto Number | Yes | Unique Lead Identifier |

| Lead Date | Date | Yes | Date enquiry received |

| Lead Time | Time | Yes | Time enquiry received |

| Lead Source | Dropdown | Yes | Facebook, Instagram, Website, QR, etc. |

| Campaign Name | Text | No | Marketing campaign name |

| Lead Status | Dropdown | Yes | New, Hot, Warm, Cold, Converted |



\---



\# Customer Information



| Field Name | Type | Mandatory | Description |

|------------|------|-----------|-------------|

| Customer Name | Text | Yes | Full customer name |

| Mobile Number | Phone | Yes | Primary contact number |

| Alternate Number | Phone | No | Secondary contact number |

| Email | Email | No | Customer email |

| City | Text | Yes | Customer city |

| State | Text | Yes | Customer state |

| Customer Type | Dropdown | Yes | Retail, Dealer, Distributor, etc. |



\---



\# Product Information



| Field Name | Type | Mandatory | Description |

|------------|------|-----------|-------------|

| Product | Dropdown | Yes | Rice variant selected |

| Quantity | Number | No | Required quantity |

| Unit | Dropdown | No | Kg, Bag, Ton |

| Requirement Type | Dropdown | No | Personal, Wholesale, Distribution |



\---



\# Follow-up Information



| Field Name | Type | Mandatory | Description |

|------------|------|-----------|-------------|

| Follow-up Date | Date | No | Next follow-up date |

| Follow-up Status | Dropdown | No | Pending, Completed |

| Telecaller Notes | Long Text | No | Internal remarks |

| Last Contact Date | Date | No | Last customer interaction |



\---



\# Sales Information



| Field Name | Type | Mandatory | Description |

|------------|------|-----------|-------------|

| Converted | Yes/No | No | Lead converted to sale |

| Order Value | Currency | No | Estimated order value |

| Expected Purchase Date | Date | No | Customer expected purchase |



\---



\# Future Fields



| Field Name | Type | Description |

|------------|------|-------------|

| Assigned Employee | Dropdown | Staff handling the lead |

| AI Lead Score | Number | AI-generated lead score |

| WhatsApp Opt-in | Yes/No | Customer consent |

| Preferred Contact Time | Dropdown | Morning, Afternoon, Evening |

| UTM Source | Text | Digital marketing source |

| UTM Campaign | Text | Campaign tracking |

| Voice AI Status | Dropdown | Future AI automation |



\---



\# Validation Rules



\- Mobile Number must contain valid digits.

\- Customer Name cannot be blank.

\- Product must be selected.

\- Lead Source is mandatory.

\- Lead Status defaults to "New".



\---



\# Data Philosophy



Collect accurate data once.



Validate it.



Reuse it across every module.



Never duplicate information.

