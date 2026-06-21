Dak Desk V7.9.1
Professional User Manual & System Documentation
Version: 7.9.1

Product Name: Dak Desk
Category: Branch Office Operations Management System
Designed For: India Post Branch Offices (BO), BPMs, ABPMs, GDS Employees
Document Version: 1.1
1. Overview
1.1 Introduction
Dak Desk V7.9.1 is a comprehensive Branch Office Management System developed to simplify and digitize
daily postal operations performed at India Post Branch Offices.
The software integrates multiple operational functions into a single unified platform, eliminating the
need to maintain separate manual registers, spreadsheets, calculators, and paper records.
Dak Desk provides tools for:
•
•
•
•
•
•
•
•
•
Daily Cash Book Management
Physical Cash Verification
BO Daily Account (BODA) Preparation
TD Incentive Bill Generation
Customer Account Ledger Management
Passbook Tracking
Maturity Monitoring
Branch Performance Analytics
PDF & Excel Reporting
The application is designed for both desktop and mobile usage and operates entirely within the
browser environment.
2. Key Objectives
The primary objectives of Dak Desk are:
Operational Efficiency
Reduce repetitive manual work performed by BPMs and ABPMs.
1
Error Reduction
Minimize mathematical and clerical mistakes through automated calculations.
Record Management
Maintain centralized digital records for accounts, customers, cash transactions, and incentive claims.
Inspection Readiness
Keep branch records organized and available for audits and inspections.
Business Development
Support CRM activities by identifying upcoming account maturities and reinvestment opportunities.
3. System Architecture
3.1 Application Type
Dak Desk is a browser-based web application.
No software installation is required.
3.2 Storage Mechanism
Data is stored locally within the browser using persistent local storage technologies.
Benefits include:
•
•
•
•
Offline functionality
Fast performance
No internet dependency
Complete local control of records
3.3 External Libraries
Dak Desk utilizes professional-grade libraries for enhanced functionality:
Library Purpose
LocalForage Local data storage
Chart.js Dashboard analytics
2
Library Purpose
jsPDF PDF generation
html2canvas Print capture
SheetJS Excel export
Lucide Icons Modern interface icons
4. User Interface Overview
The application follows a modern workspace design consisting of:
Sidebar Navigation
Provides access to all modules.
Top Navigation Bar
Contains:
•
•
•
Page Title
Theme Controls
Navigation Actions
Workspace Area
Displays the active module.
Notification System
Real-time toast notifications inform users of:
•
•
•
•
Successful saves
Errors
Warnings
Confirmations
5. Dashboard Module
Purpose
The Dashboard acts as the operational command center.
3
Dashboard Components
Current Cash Balance
Displays the latest available cash based on the most recent Cash Book entry.
TD Incentive Accrued
Displays total incentive accumulated in the active TD bill.
Total TD Entries
Shows total TD accounts currently recorded in the bill.
Accounts Opened
Displays total customer accounts recorded in the Smart Ledger.
Upcoming Maturity Alerts
Provides visibility into upcoming account maturities requiring customer engagement.
Incentive Distribution Chart
Visual representation of TD incentive performance.
Treasury Status Indicator
Displays:
•
•
•
Treasury Open
Treasury Closed
Verification Pending
6. Daily Cash Book Module
Purpose
The Daily Cash Book serves as the digital equivalent of the Branch Office cash register.
It records all cash receipts and payments occurring during the day.
4
Workflow
Step 1: Select Date
Choose the operational date.
Step 2: Verify Opening Balance
The system automatically calculates the opening balance from the previous working day.
Step 3: Record Receipts
Examples:
•
•
•
•
•
SB Deposits
RD Deposits
TD Deposits
PLI Premium Collection
Cash Received from Treasury
Required Fields:
•
•
•
Scheme
Description
Amount
Step 4: Record Payments
Examples:
•
•
•
•
Withdrawals
Treasury Remittances
Customer Payments
Miscellaneous Expenses
Required Fields:
•
•
•
Scheme
Description
Amount
Automatic Calculations
Dak Desk continuously calculates:
5
Opening Balance
•
Receipts − Payments = Closing Balance
No manual calculation is required.
Treasury Locking
After completion of daily work:
Save & Close Treasury
Functions:
•
•
•
Locks the day
Prevents accidental edits
Preserves record integrity
7. Physical Cash Tally System
Purpose
Ensures physical cash matches system-generated cash balances.
Cash Denomination Entry
Supported denominations include:
₹2000
₹500
₹200
₹100
₹50
₹20
₹10
Coins
Reconciliation Engine
Dak Desk automatically compares:
Physical Cash Count
6
vs
Cash Book Closing Balance
Status Outcomes
Balanced
Physical cash equals system balance.
Excess Cash
Physical cash exceeds system balance.
Cash Shortage
Physical cash is less than system balance.
Tally Locking
Saved tallies become permanent daily records.
These records may be used during:
•
•
•
Audits
Inspections
Internal Verification
8. Start-of-Day Verification
Before opening a new operational day:
Dak Desk requires confirmation of previous day's physical cash.
Purpose:
•
•
•
Ensure continuity of cash
Prevent opening-day discrepancies
Improve accountability
7
9. Manual Balance Override
Purpose
Provides administrative control when historical balances require correction.
Warning
Balance Override affects:
•
•
•
Opening Balance
Running Balances
Future Calculations
Use only when absolutely necessary.
Confirmation Process
The user must explicitly enter:
OVERRIDE
before activation.
10. BO Slip (BODA) System
Purpose
Generate Branch Office Daily Account summaries.
Features
•
•
•
•
Automatic cash extraction
Date integration
Remarks support
Print-ready formatting
Output
Official BO Slip suitable for operational use.
8
11. TD Incentive Bill Management
Purpose
Prepare incentive bills for Time Deposit account acquisition.
Supported Terms
TD Term Incentive Rate
1 Year 0.5%
2 Years 1.0%
3 Years 1.0%
5 Years 2.0%
Data Entry Fields
•
•
•
•
•
Account Number
Depositor Name
PR Number
Deposit Amount
Deposit Term
Automatic Incentive Calculation
The system automatically computes:
Deposit Amount × Incentive %
and generates the eligible incentive value.
Duplicate Prevention
Dak Desk detects duplicate account numbers and prevents duplicate incentive claims.
9
Live Bill Preview
Displays:
•
•
•
Calculated Incentive
Next PR Number
Updated Totals
before entry submission.
12. TD Bill Printing System
Generates official-format incentive bills.
Includes:
•
•
•
•
•
•
•
Branch Information
BPM Information
Account Listing
Total Deposits
Total Incentive
Certification Statements
Signature Blocks
13. TD Bill Export System
PDF Export
Creates printable archival copies.
Excel Export
Generates spreadsheet-compatible reports.
Print Mode
Produces direct printer-friendly output.
10
14. Smart Ledger Module
Purpose
Acts as a centralized customer relationship database.
Information Stored
Customer Details
•
•
•
•
•
Name
Mobile Number
Aadhaar
PAN
CIF
Account Details
•
•
•
•
•
Account Number
Scheme
Amount
Date
PR Number
Additional Information
•
•
•
Remarks
Nominee Details
Passbook Status
15. Passbook Tracking System
Supported statuses:
•
•
•
•
N/A
Pending AO
At BO
Delivered
Useful during inspections and customer inquiries.
16. CRM & Maturity Management
Dak Desk monitors account maturity schedules.
11
Benefits:
•
•
•
•
Customer follow-up
Reinvestment opportunities
Revenue growth
Improved customer retention
17. Reports & Analytics
Provides operational intelligence through:
•
•
•
•
•
Account Opening Reports
Incentive Analysis
Branch Growth Metrics
Cash Performance Reports
Historical Comparisons
18. POSB Scheme Reference Module
Provides quick access to:
•
•
•
•
Interest Rates
Scheme Information
Deposit Products
Customer Guidance Material
19. Settings Module
Branch Configuration
Users may define:
•
•
Branch Name
Office Details
Theme Controls
Available Modes:
•
•
Light Mode
Dark Mode
12
20. Security & Data Integrity
Dak Desk implements:
Treasury Locking
Prevents unauthorized modification.
Day Verification
Ensures continuity of balances.
Duplicate Detection
Reduces claim errors.
Confirmation Dialogs
Protects critical operations.
Override Authorization
Prevents accidental balance manipulation.
21. Recommended Daily Workflow
Morning
1.
2.
3.
Verify previous cash
Open treasury
Review dashboard
Throughout the Day
1.
2.
3.
Enter receipts
Enter payments
Register customer accounts
End of Day
1.
2.
3.
4.
Perform cash tally
Save tally
Generate BO Slip
Close treasury
13
Month End
1.
2.
3.
4.
5.
Prepare TD bill
Verify entries
Generate PDF
Export Excel copy
Archive bill
22. Changelog Summary (Observed Features in
V7.3)
New Interface
•
•
•
Redesigned modern dashboard
Responsive layout
Collapsible sidebar
Cash Operations
•
•
•
Integrated cash tally system
Start-of-day verification
Manual balance override
TD Bill Enhancements
•
•
•
Duplicate account detection
Live incentive preview
Bill history management
Smart Ledger Improvements
•
•
•
Advanced customer database
Passbook tracking
Edit functionality
Reporting
•
•
•
PDF export
Excel export
Chart-based analytics
Productivity
•
•
•
Quick action shortcuts
Dashboard maturity alerts
Dark mode support
14
23. Conclusion
Dak Desk V7.3 is a complete digital operational suite for India Post Branch Offices. By integrating cash
management, customer records, incentive billing, reporting, and maturity tracking into a single
platform, the system significantly reduces manual effort while improving accuracy, transparency, and
operational efficiency.
The software is designed to serve as the primary digital workspace for BPMs, ABPMs, and GDS
employees engaged in day-to-day Branch Office operations.
15
