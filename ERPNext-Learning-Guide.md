# Learning ERPNext

## Module 1

### 1.0 Introduction
This document assumes you are curious to know what ERPNext is about and you are interested in learning how to use it.

### 1.1 Quick overview
ERPnext is a software that runs on a linux computer (on virtualbox in any OS) or a server. You access it with a web browser.
You enter information about many things related to your company or organization:

* Customers
* Suppliers
* Sales
* Accounting
* Inventory of Items (Stock)
* Projects
* Manufacturing
* Retail sales

It is also incorporating several domain specific functions for industries such as:

* Education
* Agriculture
* Healthcare
* Non-Profits


ERPNext already has basic documentation, videos and a support group with plenty of community members that can support you on your journey to learn how to use this software.


### 1.2 Structure
The following course or tutorial is divided into 5 modules, which will enable you to master ERPNext.

> * Module 1: Introduction to ERPNext
> * Module 2: Basic usage
> * Module 3: Intermediate usage
> * Module 4: Advanced usage
> * Module 5: Becoming an expert

This course is divided in 5 modules. Each module will take your learning from the general
to the more specific, in the same manner that we talk about a ship in general terms, each 
additional module will explore the topics with more specificity about the ship, such as 
propulsion systems, bilge systems, navigation, crew, etc. At the end we will reach detailed
explanations about individual ship components such as engines, pumps, compass, captain's duties, etc.
With this, you can revise the basics or go down to the details when necessary to master ERPNext.

I personally like a specific order to better refer to topics in a structured manner, so I have
numbered items by levels, separated by decimals. Each module is at a level 1. Level 2 is represented
by a level one number, separated by a decimal and another number, and then another number
that begins the ordinal count of the topic within the module.
You can refer to a specific topic by the number. This also will help when indexing.
Each sub-topic is separated by a decimal point from the number that represents the parent or principal topic.

### 1.3 Module 1 Objective
- How to access or install and configure ERPNext
You use any web browser to manage anything related to ERPNext system.

You can run it locally on a linux machine, or in a virtual server on any operating system.

Ideally you use a web server with a public IP address so you can access the service from any internet
connected device.

This module focuses on learning to set it up, configuring it and use this instance to 
satisfy the basic accounting and management needs of a business or non-profit.

### 1.4 Getting an instance of ERPNext

#### 1.4.1 Trial account on  erpnext.com
The quickest and easiest way to learn it, is to open a trial account on [erpnext.com](https://www.erpnext.com)
Once set up, jump straigh to Module 2.

#### 1.4.2 - Local installation in any operating system with VirtualBox
The next easiest way is to download a pre-installed virtual image to use with Oracle's VirtualBox.
Download VirtualBox from [here](https://www.virtualbox.org/)
Since ERPNext is [open source software](https://en.wikipedia.org/wiki/Open-source_license),
 you can download a production image directly from this site and use for any purpose allowed in the license:
[https://erpnext.com/download](https://erpnext.com/download)
You run virtualBox, import the appliance and start the server. Make sure you configure the
virtual networking cards properly. I usually use a Bridged adapter to my existing WiFi
connection on a MAC so that the virtual machine gets an IP address from my router. This way, I can
access it using a local IP address on the web browser.

## Module 2:  Basic use

In this module we will learn how to use the program, how to configure the most important basics
how to find help for specific questions and we will explore the concept of the DocTypes.

The rest of the module will be an initial exploration of the program modules for

* Accounting
* Human Resources
* Stock or Inventory
* Buying
* Selling
* CRM (Customer Resource Management)
* Manufacturing
* Projects
* Assets
* Web Site

### 2.0 Module 2 objectives

- Basic operation of the Frappé/ ERPNext Framework
- Configure ERPNext to manage products and services for purchase or sale
- Configure your accounts, product and service groups
- Manage suppliers and customers
- Make a purchase cycle (from quotation to payment)
- Make a sales cycle (from a lead to receiving the customer's payment)
- Manage stock

### 2.1 Basic Operation
#### 2.1.1 How to Login (Video 002)
#### 2.1.2 Configure your user (Video 003)
##### 2.1.2.0 Configure your desktop icons (Video 004)
##### 2.1.2.1 Add a user (Video 005)
#### 2.1.3 Frappe Framework basics (Video 006)
* Images
* Attachments
* Assignments
* Labels
* Users
* Sharing
* Time of creation and editing
* Comments
* Specific DocType action buttons
* The **Make** Button
* Duplicating documents
	I consider this particular feature of ERPNext one of the most useful for day to day
	transactions, because it allows you to copy data from an existing DocType such as a 
	purchase order and create a new one with the same items, just changing the amount and date
	or other parameters to suit this particular doctype instance.
	
##### 2.1.3.1 DocTypes: Main and supporting (Video 007)
Example: A main or master DocType is one such as Item or Sales Invoice. A supporting DocType is 
an Item Attribute or a Sales Invoice Item

* User
* Item
* Item Price
* Customizing (adding fields)
* Series and numbering

#### 2.1.4 Where to find support and help (Video 008)
[Documentation](https://erpnext.org/docs/user/manual)
[YouTube Video Channel](https://www.youtube.com/c/erpnext)
[Discussion Forum](https://discuss.erpnext.com/)
[Chapters](https://erpnext.org/chapters)

### 2.2 Program modules
#### 2.2.1 - Accounts
##### 2.2.1.1 - Company (Video 009)
##### 2.2.1.2 - Cost centers (Creating cost centers) (Video 010)
##### 2.2.1.3 - Chart of accounts or Account tree (creating accounts) (Video 011)
##### 2.2.1.4 - Journal Entry (Accounting entry) (Video 012)
##### 2.2.1.5 - Opening Entry (Video 013)
#### 2.2.2 - Human Resources
##### 2.2.2.1 - Employees (Video 014)
##### 2.2.2.2 - Branch (Video 015)
##### 2.2.2.3 - Department (Video 016)
##### 2.2.2.4 - Designation (Video 017)
#### 2.2.3 - Stock
##### 2.2.3.1 - Item Groups (creating groups) (Video 018)
##### 2.2.3.2 - Warehouse (creating warehouses) (Video 019)
##### 2.2.3.3 - Items (Video 020)
	The importance of marking (or not) the checkbox "Maintain stock"
#### 2.2.4 - Buying
##### 2.2.4.1 - Add a supplier (Video 021)
##### 2.2.4.2 - Modify suppliers (Video 022)
##### 2.2.4.3 - Add a quotation from the supplier (Video 023)
##### 2.2.4.4 - Adding a purchase (Video 024)
##### 2.2.4.5 - Full purchase Cycle: Supplier quotation, purchase order, purchase receipt, purchase invoice and payment  (Video 025)
#### 2.2.5 - Selling
##### 2.2.5.1 - Add a customer  (Video 026)
##### 2.2.5.2 - Modify customers  (Video 027)
##### 2.2.5.3 - Add quotation for the customer (Video 028)
##### 2.2.5.4 - Adding a sale  (Video 029)
##### 2.2.5.5 - CFull sales cycle:  Customer quotation, sales order, delivery note, sales invoice, payment request and payment (Video 030)
#### 2.2.6 - CRM (Customer Resource Management)
##### 2.2.6.1 - Use of CRM to increase sales and customer service (Video 031)
##### 2.2.5.2 - Leads and Opportunities (Video 032)
##### 2.2.5.3 - Campaigns (Video 033)
#### 2.2.7 - Manufacture
##### 2.2.7.1 - Bill of Materials (Video 034)
	For manufacture or subcontracting
#### 2.2.8 - Projects
##### 2.2.8.1 - Internal project with tasks and progress (Video 035)
#### 2.2.9 - Assets
##### 2.2.7.2 Asset category (Video 036)
##### 2.2.7.1 Creating an asset(Video 037)
#### 2.2.10 - Web Site
##### 2.2.10.1 - Creating a Web Page (Video 038)
### 2.3 Module 2 Conclusion

In this module we have learned the most basic and important aspects of ERPNext.
We learned how to login, configure your user, configure your desktop icons, select your
language, access the configuration menu and added a user.

We also learned about the very important Frappé framework, which empowers ERPNext beyond just
the main and support DocTypes, especially its functionality allowing assignments of
documents to other users, attaching files to these documents, sharing individual documents
whose individual permits are restricted to certain users, track all activities on a document
chronologically and by author, including the comments and communications that can be placed directly on the DocType.
We also learned how to search for help and support.

We then initiated our exploration of the accounting modules by creating a company, cost centers,
accounts and learning how to create accounting entries.

We saw the human resource module where we created the first employee. We moved to the stock
module where we learned the importance of properly grouping items, an example of a coding scheme
the creation of a pair of warehouses and then we learned to create items.  Items are some of the most
crucial parts of ERPNext.

After this we moved to know about the Buying module where we created a supplier, modified it
made a quotation as furnished by the supplier, then a direct purchase, and finally a more formal
purchase which includes a supplier quotation, purchase order, purchase receipt, purchase invoice and payment.

We saw then the same process, now in the Selling module, where we added a customer, modified its data,
added a quotation to the customer and finally generated a more formal sale (sales cycle)

We checked how to use the CRM module to manage potential customers, allowing us to increase the 
service to the customer, create marketing campaigns and track leads until converting them to customers.

We checked the manufacturing module and its underpinning: The **Bill of Materials (BOM)** which allowed us
to define which raw materials are needed for a specific product.

The Projects module was overseen, with the creation of a simple internal project with tasks and due dates.
The assets module with its categories and assets, which we will learn how to depreciate and maintain in the next module.
The WebSite module allowed us to create a simple webpage to serve to all users accesing from the web

## Module 3: Intermediate Use
### 3.1 Intermediate use
#### 3.1.1 - Roles (Video 039)
#### 3.1.2 - Permissions (Video 040)
#### 3.1.3 - Series and Numbering (Video 041)
#### 3.1.4 - System settings (Video 042)
#### 3.1.5 - Global settings (Video 043)
#### 3.1.6 - Account settings (Video 044)
#### 3.1.7 - Configuring e-mail account (Video 045)
#### 3.1.8 - Print settings (Video 046)
#### 3.1.9 - Personalized translations (Video 047)
#### 3.1.10 - Additional Setup (Setup Module)  MORE WORK NEEDED HERE
### 3.2 Program modules
#### 3.2.1 - Accounts
##### 3.2.1.1 - Fiscal Year  (Video 048)
##### 3.2.1.2 - Currency (Video 049)
##### 3.2.1.3 - POS Configuration (Video 050)
##### 3.2.1.4 - Payment methods(Video 051)
##### 3.2.1.5 - Payment entry (Video 057)
##### 3.2.1.6 - Taxes (Selling) (Video 053)
##### 3.2.1.7 - Taxes (Buying) (Video 054)
##### 3.2.1.8 - Sales Invoice (Video 055)
##### 3.2.1.9 - Purchase Invoice (Video 056)
##### 3.2.1.10 -  Conciliation of Payments(Video 057)
#### 3.2.2 - Human Resources
##### 3.2.2.1 - Human Resources Configuration (Video 058)
##### 3.2.2.2 - Holiday List (Video 059)
##### 3.2.2.3 - Salary structure and components (Video 060)
##### 3.2.2.4 - Payroll entry (Video 061)
##### 3.2.2.5 - Payroll entry tool (Video 062)
##### 3.2.2.6 - Configuring daily work summary (Video 063)
#### 3.2.3 - Stock
##### 3.2.3.1 - Units of Measure (Video 064)
##### 3.2.3.2 - Brands (Video 065)
##### 3.2.3.3 - Stock configuration (Video 065)
##### 3.2.3.4 - Item Variant Settings  (Video 209)
##### 3.2.3.5 - Price List (Video 066)
##### 3.2.3.6 - Stock entry (Inventory movements) (Video 067)
* Initial loading of inventory or stock
	1. Go to Stock module
	2. Select Stock entry
	3. Click on New
	4. Purpose: Material receipt
	5. Indicate destination Warehouse
	6. Enter the name or code of the product, where it says: Item Code
	7. Indicate the quantity to add or load in the inventory.
	8. Repeat for each desired product
	9. If no net rate or value is indicated by ERPNext (Purchase rat eminus sales tax), it will ask for it.
	10. Click on **Save**, and then **Submit**
##### 3.2.3.7 - Stock opening entry(Video 068)
##### 3.2.3.8 - Material request (Video 069)
##### 3.2.3.9 - Purchase Receipt (Video 070)
#### 3.2.4 - Buying
##### 3.2.4.1 - Buying configuration (Video 071)
##### 3.2.4.2 - Product Bundle(Video 001)
 Important:  If you changed the default warehouse AFTER having created a product bundle, make sure you refresh or reload the page.
##### 3.2.4.3 - Buying terms and conditions (Video 072)
##### 3.2.4.4 - Supplier scorecard (Video 073)
##### 3.2.4.5 - Supplier qualification criteria (Video 074)
##### 3.2.4.6 - Supplier qualificaiton variable (Video 075)
#### 3.2.5 - Selling
##### 3.2.5.1 - Selling Configuration (Video 076)
##### 3.2.5.2 - Industry type (Video 077)
##### 3.2.5.3 - Territory(Video 078)
##### 3.2.5.4 - Sales Partner(Video 079)
##### 3.2.5.5 - Sellers (Video 080)
##### 3.2.5.6 - Product Bundle (Video 001) - Revisited
##### 3.2.5.7 - Selling terms and conditions (Video 081)
##### 3.2.5.8 - Selling by means of POS (Video 082)
#### 3.2.6 - CRM (Customer Resource Management)
##### 3.2.6.1 - Customer Category (Video 083)
##### 3.2.6.2 - Communications (Video 084)
##### 3.2.6.3 - SMS Settings for mobile messaging from ERPNext (Video 085)
#### 3.2.7 - Manufacturing
##### 3.2.7.1 - Subcontracting (Video 086)
##### 3.2.7.2 - Production Order (Video 087)
##### 3.2.7.3 - Timesheet (Video 088)
#### 3.2.8 - Projects
##### 3.2.8.1 - Types of Projects (Video 089)
##### 3.2.8.2 - Type and Activity Cost (Video 090)
##### 3.2.8.3 - Project Tasks (Video 091)
##### 3.2.8.4 - Timesheet (Video 092)
#### 3.2.9 - Assets
##### 3.2.9.2 - Asset Maintenance Team (Video 093)
##### 3.2.9.3 - Asset Maintenance (Video 094)
##### 3.2.9.4 - Asset Maintenance Log Entry (Video 095)
##### 3.2.9.5 - Asset Repair (Video 096)
#### 3.2.10 - Tools
##### 3.2.10.1 - Tasks(Video 097)
##### 3.2.10.2 - Files (Video 098)
##### 3.2.10.3 - Calendar (Video 099)
##### 3.2.10.4 - Chat (Video 100)
##### 3.2.10.5 - Note (Video 101)
##### 3.2.10.6 - Activity (Video 102)
##### 3.2.10.7 - E-mail group (Video 103) 
##### 3.2.10.8 - Newsletter (Video 104)
#### 3.2.11 - Web Site
##### 3.2.11.1 - Web Site Configuration (Video 105)
##### 3.2.11.2 - Company Information Configuration (Video 106)
##### 3.2.11.3 - Contact Configuration (Video 107)
##### 3.2.11.4 - Web site Theme (Video 108)
##### 3.2.11.5 - Portal Configuration (Video 109)
##### 3.2.11.6 - Main Page (Video 110)
##### 3.2.11.7 - Blog Configuration (Video 111)
##### 3.2.11.8 - Blog Entry (Video 112)
### 3.3 Module 3 Conclusion

## Module 4: Advanced Use
What we will see here
### 4.1 Advanced Operation
#### 4.1.3 - Domain Specific Configuration
##### 4.1.3.1 - Agriculture Module (Video 113)
##### 4.1.3.2 - Hospitality Module(Video 114)
##### 4.1.3.3 - Healthcare Module (Video 115)
##### 4.1.3.4 - Education Module (Video 116)
##### 4.1.3.6 - Services Module (Video 117)
##### 4.1.3.7 - Manufacture Module (Video 118)
#### 4.1.2 - Data Backups (Video 119)
#### 4.1.3 - Form Customization (Video 120)
	A best practice to use here is to prepend the name of your company to field names (A good practice to prevent errors when updating. You can always copy data from one field to another (column) using mariadb commands later)
	Adding new fields to main doctypes (Customize)
#### 4.1.4 - Personalized Fields (Video 121)
		A best practice to use here is to prepend the name of your company to field names (A good practice to prevent errors when updating. You can always copy data from one field to another (column) using mariadb commands later)
		This particular instruction helps with child table doctypes
#### 4.1.5 - Custom scripts(Video 122)
#### 4.1.6 - Email notifications (Video 123)
#### 4.1.7 - Print formats (Video 124)
	Basic jinja for print templates
	Examples
#### 4.1.8 - Print Style (Video 125)
#### 4.1.9 - Print Format Builder (Video 126)
### 4.1.10 - Address Format (Video 127)

### 4.2 Program Modules
#### 4.2.1 - Accounts
##### 4.2.1.1 - Trial Balance (Video 128)
##### 4.2.1.2 - Payment request (Video 129)
##### 4.2.1.3 - Accounts receivable (Video 130)
##### 4.2.1.4 - Accounts payable (Video 131)
##### 4.2.1.5 - Bank reconciliation statements (Video 132)
##### 4.2.1.6 - Bank change summary (Video 133)
##### 4.2.1.7 - Bank guarantee (Video 134)
##### 4.2.1.8 - Fiscal rule (Video 135)
##### 4.2.1.9 - Budget (Video 136)
##### 4.2.1.10 - Budget Variance (Video 137)
##### 4.2.1.11 - Monthly Distrubtion  for Budgets (Video 138)
##### 4.2.1.12 - Period closing (Video 139)
#### 4.2.2 - Human Resources
##### 4.2.2.1 - Attendance (Video 140)
##### 4.2.2.2 - Employee Attendance Tool (Video 141)
##### 4.2.2.3 - Upload Attendance (Video 142)
##### 4.2.2.4 - Leave Application (Video 143)
##### 4.2.2.5 - Leave type (Video 144)
##### 4.2.2.6 - Leave Allocation (Video 145)
##### 4.2.2.7 - Leave Allocation Tool (Video 146)
##### 4.2.2.8 - Leave Block List (Video 147)
#### 4.2.3 - Stock
##### 4.2.3.1 - Product Attributes (Video 148)
##### 4.2.3.2 - Product Variants (Video 149)
##### 4.2.3.3 - Stock Reconciliation (Video 150)
##### 4.2.3.4 -  Packing List (Video 151)
##### 4.2.3.5 - Series Numbering (Video 152)
##### 4.2.3.6 - Lot Number (Video 153)
#### 4.2.4 - Buying
##### 4.2.4.1 - Inviting suppliers to the ERPNext portal  for your Company (Video 154)
##### 4.2.4.2 - Entering supplier quotation on your ERPNext portal (Video 155)
#### 4.2.5 - Selling
##### 4.2.5.1 - Shipping Rule (Video 156)
##### 4.2.5.2 - Sales Analytics (Video 157)
##### 4.2.5.3 - Customer loyalty (Video 158)
#### 4.2.6 - CRM (Customer Resource Management)
###### 4.2.6.1 - SMS Entry (Video 159)
###### 4.2.6.2 - SMS Settings (Video 160)
##### 4.2.7 - Manufacturing
##### 4.2.7.1 - Open Production Orders(Video 161)
##### 4.2.7.2 - Production Orders in Progress (Video 162)
##### 4.2.7.3 - Delivered products from Production Orders (Video 163)
##### 4.2.7.4 - Completed Production Orders (Video 164)
##### 4.2.7.5 - Production Analysis (Video 165)
#### 4.2.8 - Projects
##### 4.2.8.1 - Daily work hour summary (Video 166)
##### 4.2.8.2 - Precise stock measurement (Video 167)
#### 4.2.9 - Assets
##### 4.2.9.1 - Asset movement (Video 168)
##### 4.2.9.2 - Asset depreciations and pending balance (Video 169)
### 4.3 Module 4 Conclusion
Conclusion and summary of what we saw here.

## Module 5: Becoming an expert
What to expect
### 5.1 Expert level operation
#### 5.1.1 Application installer (Video 170)
#### 5.1.2 Email alerts (Video 171)
#### 5.1.3 Standardized response (Video 172)
#### 5.1.4 Feedback trigger (Video 173)
#### 5.1.5 Email summary (Video 174)
#### 5.1.6 Account payment vía gateway (Cuenta pasarela de pago) (Video 175)
#### 5.1.7 - Check printing template (Video 176)
#### 5.1.8 - Programming advanced invoice templates (Video 177)
### 5.2 Program modules
#### 5.2.1 - Accounts
##### 5.2.1.1 - Report Gross profit (Video 178)
##### 5.2.1.2 - Purchase Invoice Trends (Video 179)
##### 5.2.1.3 - Sales Invoice Trends (Video 180)
##### 5.2.1.4 - Trial Balance for Party (Video 181)
##### 5.2.1.5 - Payment Period Based on Invoice Date (Video 182)
##### 5.2.1.6 - Sales Partner Comission (Video 183)
##### 5.2.1.7 - Item-wise Sales Register (Video 184)
##### 5.2.1.8 - Item-wise Purchase Register (Video 185)
##### 5.2.1.9 - Accounts Receivable Summary (Video 186)
##### 5.2.1.10 - Accounts Payable Summary NO VIDEO ASSIGNED
##### 5.2.1.11 - Sales Payment Summary (Video 187)
##### 5.2.1.12 - Creating and Saving Personalizados Reports (Video 188)
#### 5.2.2 - Human Resources
##### 5.2.2.1 - Appraisal (Video 189)
##### 5.2.2.2 - Appraisal Template (Video 190)
##### 5.2.2.3 - Team Updates (Video 191)
##### 5.2.2.4 - Training Program (Video 192)
##### 5.2.2.5 - Training Event (Video 193)
##### 5.2.2.6 - Training Result(Video 194)
##### 5.2.2.7 - Training Feedback (Video 195)
##### 5.2.2.8 - Loan Type (Video 196)
##### 5.2.2.9 - Employee Loan Application (Video 197)
##### 5.2.2.10 - Employee Loan (Video 198)
##### 5.2.2.11 - Vehicle
##### 5.2.2.12 - Vehicle Log
##### 5.2.2.13 - Reports
###### 5.2.2.13.1 - Employee Birthday (Video 199)
###### 5.2.2.13.2 - Employee Leave Balance (Video 200)
###### 5.2.2.13.3 - Employees working on a holiday (Video 201)
###### 5.2.2.13.4 - Employee information (Video 202)
###### 5.2.2.13.5 - Salary Register (Video 203)
###### 5.2.2.13.6 - Monthly Attendance Sheet (Video 204)
###### 5.2.2.13.7 - Vehicle Expenses (Video 205)
#### 5.2.3 - Stock
##### 5.2.3.1 - Delivery Trip (Video 206)
##### 5.2.3.2 - Quality Inspection (Video 207)
##### 5.2.3.3 - Landed Cost Voucher (Video 208)
##### 5.2.3.4 - Instalation Note (Video 210)
##### 5.2.3.5 - Serial Number Service Contract Expiry NO VIDEO
##### 5.2.3.6 - Serial Number Status NO VIDEO
##### 5.2.3.7 - Serial Number Warranty Expiry NO VIDEO 
##### 5.2.3.8 -  Stock Reports
###### 5.2.3.8.1 - Stock Ledger (Video 211)
###### 5.2.3.8.2 - Stock Balance (Video 212)
###### 5.2.3.8.3 - Stock Projected Quantity (Video 213)
###### 5.2.3.8.4 - Stock Summary (Video 214)
###### 5.2.3.8.5 - Stock Ageing (Video 215)
###### 5.2.3.8.5 - Item Price Stock (Video 216)
##### 5.2.3.9 - Additional reports
###### 5.2.3.9.1 - Ordered Items To Be Delivered (Video 217)
###### 5.2.3.9.2 - Purchased Order Items To Be Received(Video 218)
###### 5.2.3.9.3 - Item Shortage Report (Video 219)
###### 5.2.3.9.4 - Requested Items To Be Transferred (Video 220)
###### 5.2.3.9.5 - Batch-Wise Balance History (Video 221)
###### 5.2.3.9.6 - Estado de caducidad de lote de productos (Video 222)
###### 5.2.3.9.7 - Precios de los productos (Video 223)
###### 5.2.3.9.8 - Nivel recomendado de reabastecimiento de producto (Video 224)
###### 5.2.3.9.9 - Detalles de la variante del articulo (Video 225)
#### 5.2.4 - Buying
##### 5.2.4.1 - Items to Be Requested (Video 226)
##### 5.2.5.2 - Requested Items To Be Ordered (Video 227)
##### 5.2.5.3 - Material Requests for which Supplier Quotations are not Created (Video 227)
##### 5.2.5.4 - Item-Wise Purchase History (Video 228)
##### 5.2.5.5 - Supplier Addresses And Contacts (Video 229)
#### 5.2.5 - Selling
##### 5.2.5.1 - Lead Details (Video 230)
##### 5.2.5.2 - Customer Addresses and Contacts (Video 231)
##### 5.2.5.3 - Ordered Items to Be Delivered (Video 232)
##### 5.2.5.4 - Sales Person-wise Transaction Summary (Video 233)
##### 5.2.5.5 - Item-Wise Sales History (Video 234)
##### 5.2.5.6 - Bill Of Materials (BOM) Search (Video 235)
##### 5.2.5.7 - Inactive Customers (Video 236)
##### 5.2.5.8 - Available Stock For Packing Items (Video 237)
##### 5.2.5.9 - Pending SO Items For Purchase Request (Video 238)
##### 5.2.5.10 - Customer Credit Balance (Video 239)
##### 5.2.5.11 - Custom Reports for Selling (Video 240)
#### 5.2.6 - CRM (Customer Resource Management)
##### 5.2.6.1 - Lead Details (Also seen in Selling) (Video 241)
##### 5.2.6.2 - Sales Funnel (Video 242)
##### 5.2.6.3 - Prospects Engaged But Not Converted (Video 243)
##### 5.2.6.4 - Minutes To First Response for Opportunity (Video 244)
##### 5.2.6.5 - Inactive Customers (Video 245)
##### 5.2.6.6 - Campaign Efficiency (Video 246)
##### 5.2.6.7 - Lead Owner Efficiency (Video 247)
#### 5.2.9 - Assets
##### 5.2.9.1 - Asset Movement Tool (Video 248)
##### 5.2.9.2 - Asset Depreciation Ledger (NO VIDEO NUMBER ASSIGNED)
#### 5.2.10 - Maintaining the Software
##### 5.2.10.1 - Accesing the Command Line (Video 250)
##### 5.2.10.2 - Terminal and/or iTerm (Video 251)
##### 5.2.10.3 - Creating snapshots (VirtualBox, or otther options) (Video 252)
##### 5.2.10.4 - Remote Server Installation NO ASSIGNED VIDEO
##### 5.2.10.5 - Setting up SSL with Let's Encrypt NO ASSIGNED VIDEO
##### 5.2.10.6 - The ERPNext folder: Frappe-Bench (Video 253)
##### 5.2.10.7 - Updating the Application NO ASSIGNED VIDEO
##### 5.2.10.8 - GitHub y Versiones de control (Video 256)
##### 5.2.10.9 - Modo desarrollador y consola desarrollo del navegador (Video 257)

### 5.3 Module 5 Conclusion

## Module 6: Manufacturing (Missing or advanced topics)
These topics have been reviewed, but perhaps a couple of example videos explaining an entire workflow or more advanced concepts or cases.
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/manufacturing)

## Module 7: Services (Missing or advanced topics)
These topics have been reviewed, but perhaps a couple of example videos explaining an entire workflow or more advanced concepts or cases.
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/projects)

## Modulo 8: Point of Sale
## 8.1 - POS
### 8.1.1 - How it works
### 8.1.2 - Configuring POS
### 8.1.3 - How to make a POS sale
### 8.1.4 - Using without Internet access - Local data storage

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/accounts/point-of-sale-pos-invoice)

## Module 9: Stock Module Additional Topics
## 9.1 - Stock and Distribution topics
### 9.1.1 - Purchase returns
### 9.1.2 - Sale return
### 9.1.3 - Sample Inventories

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/stock)

## Module 10: Education
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/education)

## Module 11: Agriculture
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/agriculture)

## Module 12: Healthcare
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/healthcare)


# WORK IN PROGRESS BELOW DISREGARD




#### 5.2.10 - Modifying the Software from the base
##### 5.2.10.5 - Modifying Files (Video 254)
##### 5.2.10.6 - Modifying Reports  - Query report (Adding Columns) (Video 255)
##### 5.2.10.9 - Creating reports - Pages  (Ex. Sales Analytics, vs. Sales Analytics 2.0) (Video 258)
