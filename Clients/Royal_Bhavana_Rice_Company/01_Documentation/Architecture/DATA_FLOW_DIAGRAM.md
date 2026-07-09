\# Royal Bhavana Rice Company

\# Data Flow Diagram (DFD)



\---



\# Purpose



This document explains how customer information flows through the Royal Bhavana Rice Company Lead Management Platform.



\---



\# Level 0 DFD (High-Level)



Customer



↓



Landing Page



↓



Lead Enquiry Form



↓



Google Form



↓



Google Sheets Database



↓



CRM Dashboard



↓



Telecaller



↓



Customer Follow-up



↓



Order Confirmation



\---



\# Level 1 DFD



\## Step 1 – Customer Visit



Customer visits the Landing Page from:



\- Facebook

\- Instagram

\- Google Search

\- Google Business Profile

\- QR Code

\- WhatsApp

\- Direct Link

\- E-commerce Platforms



↓



\## Step 2 – Landing Page Interaction



Customer can:



\- Read Company Information

\- Browse Products

\- View Contact Details

\- Open WhatsApp

\- Visit Social Media

\- Visit E-commerce Platforms

\- Submit an Enquiry



↓



\## Step 3 – Lead Submission



Customer enters:



\- Name

\- Mobile Number

\- City

\- State

\- Customer Type

\- Product Requirement

\- Quantity

\- Message



↓



Google Form validates the data.



↓



\## Step 4 – Database Storage



Google Form automatically stores:



\- Lead ID

\- Date

\- Time

\- Customer Details

\- Product Interest

\- Lead Source

\- Status = New



↓



Google Sheets Database



↓



\## Step 5 – CRM Dashboard



Telecaller reviews:



\- New Leads

\- Hot Leads

\- Warm Leads

\- Cold Leads

\- Follow-up Pending

\- Converted Leads



↓



Updates:



\- Lead Status

\- Notes

\- Follow-up Date

\- Remarks



↓



\## Step 6 – Sales Process



If customer confirms:



↓



Order Generated



↓



Customer marked as Converted



↓



Sales Report Updated



\---



\# External Systems



Facebook



↓



Landing Page



Instagram



↓



Landing Page



Google Business Profile



↓



Landing Page



WhatsApp



↓



Customer Communication



Google Maps



↓



Location



E-commerce Platforms



↓



Product Purchase



\---



\# Future Data Flow



Landing Page



↓



Supabase



↓



CRM Portal



↓



Employee Portal



↓



Manager Dashboard



↓



AI Analytics



↓



WhatsApp Automation



↓



Voice AI



\---



\# Data Validation



Mandatory Fields:



\- Customer Name

\- Mobile Number

\- Product Requirement



Optional Fields:



\- Email

\- Remarks



\---



\# Data Backup



Primary Database



↓



Google Sheets



↓



Automatic Google Cloud Backup



↓



Manual GitHub Documentation Backup



\---



\# Design Objective



Collect data once.



Store it safely.



Use it everywhere.



Never ask the customer twice.

