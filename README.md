# 📋 Purchase Requisition Form Management System

An advanced Excel-based purchase requisition system designed for organizations to streamline procurement approvals, manage multi-company orders, track vendor expenses, and generate professional requisition forms with automated data validation and duplicate detection.

## 📋 Overview

This system solves critical procurement challenges: **How to manage purchase requests efficiently across multiple companies, departments, and vendors while preventing duplicate orders and ensuring proper approval workflows.**

The system helps procurement teams by:
- **Automated Form Generation**: Select requisition number and print instantly (Ctrl+P)
- **Duplicate Detection**: Automatically identifies if material was ordered previously
- **Multi-Company Support**: Manage purchases for multiple companies in one system
- **Vendor Management**: Track all vendors and expense types
- **Approval Workflow**: Manager, Executive, and Director approval tracking
- **Data Validation**: Dropdown menus ensure consistent data entry
- **Instant Reporting**: All requisition data in a single master sheet

## 📸 View & Play with the File

**[Access Purchase Requisition System](https://excel.cloud.microsoft/open/onedrive/?docId=3B61701CAABF1310%21s4bb5ab51c44c439eaae4f75464c6a01a&driveId=3B61701CAABF1310)**

> Click the link above to access the live system in Excel Online

## 📊 System Screenshots

### Purchase Requisition Form (Print-Ready)
<img width="1359" height="719" alt="1" src="https://github.com/user-attachments/assets/cb43feee-68af-419d-a6cc-d44420d957fb" />

*Professional requisition form ready for printing with all details auto-filled from data sheet*

### Data Entry Sheet with Duplicate Detection
<img width="1362" height="720" alt="2" src="https://github.com/user-attachments/assets/1a98008c-76ef-4ddd-82d4-312fadeca711" />

*Centralized data management with automatic duplicate detection and dropdown validation*

### Validation Sheet - Master Data Setup
<img width="1359" height="716" alt="3" src="https://github.com/user-attachments/assets/2df48599-3d0c-4cf0-9046-34dc6e2e6054" />

*Master data configuration for companies, vendors, managers, and departments*

## 🎯 Why This System Was Built

Organizations face common procurement challenges:
- Manual requisition forms take too much time to prepare
- Duplicate orders waste money and create confusion
- Hard to track requisitions across multiple departments/companies
- Approval workflows are unclear
- Vendor and expense type data is inconsistent
- Difficult to maintain historical procurement records

This system automates the entire process from data entry to form generation.

## ✨ Key Features

### 1. Automated Requisition Form Generation
- **One-Click Printing**: Select requisition number → Ctrl+P → Done!
- **No Manual Formatting**: Form automatically populates from data
- **Professional Layout**: Clean, printable format for approvals
- **Auto-Calculations**: Total amount calculated automatically
- **Signature Fields**: Prepared by, Approved by, Authorised by sections

### 2. Intelligent Duplicate Detection
- **Automatic Checking**: Flags if material was previously ordered
- **Month-wise Tracking**: Shows "Duplicate" if same item is ordered in the current/previous month
- **Visual Alerts**: Clear "It's Duplicate" indicator in data sheet
- **Prevents Waste**: Stops redundant orders before they happen

### 3. Multi-Company Management
- **Single System**: Manage requisitions for multiple companies
- **Company Dropdown**: Easy selection from validated list
- **Company-Specific Tracking**: Filter requisitions by company
- **Examples**: BlueRock Advisors, NexaSoft Solutions, FreshWave Services, AutoShine Hub

### 4. Comprehensive Data Management
One master "Data" sheet contains all requisition information:
- **Sr. No.**: Sequential numbering
- **Duplicate Check**: Automatic validation (Yes/No/Its Duplicate)
- **Company Name**: Which company is ordering
- **Requisition Number**: Auto-generated (Admin/PUNE/03/25-26/MAT-01 format)
- **Date**: When requisition was created (DD-MM-YYYY format)
- **Manager Name**: Who is approving
- **Project/Department**: Which department needs the items
- **Requested By**: Employee making the request
- **Authorised By**: Final approver
- **Vendor Name**: Supplier details
- **Expense Type**: Category (Coffee Material, HK Material, Stationery, Medicine)

### 5. Vendor & Expense Type Management
Track diverse procurement needs:
- **Vendors**: Orion TradeCorp, NovaEdge Solutions, AquaLeaf Drinks, etc.
- **Expense Types**:
  - Coffee Material
  - HK Material (Housekeeping)
  - Stationery Material
  - Medicine Material
- **Department Tracking**: Administration, Finance, Human Resources, IT Operations, Procurement

### 6. Smart Requisition Numbering
Automatic numbering format: `Admin/PUNE/MM/YY-YY/MAT-XX`
- **Location-based**: PUNE or other locations
- **Year-based**: 03/25-26 (March 2025-2026)
- **Sequential**: MAT-01, MAT-02, MAT-03...
- **No Duplicates**: System ensures unique numbers

### 7. Approval Workflow Tracking
Clear approval hierarchy:
- **Requested By**: Employee initiating request (e.g., Jesika Mehta)
- **Prepared By**: Person preparing the requisition
- **Approved By**: Manager/Department Head (e.g., Vikas Patil)
- **Authorised By**: Executive/Director (e.g., Amit Khanna)
- **Signature Fields**: Space for physical signatures on printed form

### 8. Data Validation & Consistency
Dropdown menus prevent errors:
- **Company Names**: Pre-defined company list
- **Manager Names**: Select from employee list
- **Departments**: Validated department options
- **Expense Types**: Fixed category list
- **Vendor Names**: Approved vendor list only

### 9. Flexible Reporting
- **Single Data Source**: All requisitions in one sheet
- **Easy Filtering**: Filter by company, date, department, vendor
- **Historical Tracking**: Complete procurement history
- **Export Capability**: Data can be used for analysis

### 10. Print-Optimized Design
- **Perfect Layout**: Form fits on one page
- **Professional Appearance**: Clean borders and formatting
- **Logo Ready**: Space for company logo (top left)
- **Signature Lines**: Clear spaces for all approvers

## 🚀 Complete Step-by-Step Guide - How to Use

### 📥 PART 1: Initial Setup (One-Time, 10 Minutes)

#### **Step 1: Download and Open the File**
1. Click the **[Access Link](https://excel.cloud.microsoft/open/onedrive/?docId=3B61701CAABF1310%21s4bb5ab51c44c439eaae4f75464c6a01a&driveId=3B61701CAABF1310)**
2. File → **Download a Copy** (if using Excel Online)
3. Open in **Microsoft Excel** (2016 or later)
4. Save as: `"PurchaseRequisition_YourCompany_2025.xlsx"`

---

#### **Step 2: Configure Your Companies**
1. Go to **"Validation"** sheet (bottom tab)
2. Find **"Company Name"** column (Column A)
3. **Review the default companies:**
   - BlueRock Advisors
   - NexaSoft Solutions
   - FreshWave Services
   - AutoShine Hub
   - PixelGrow Agency
   - UrbanDesk Workspaces
   - (and 17 more...)

4. **Customize for YOUR organization:**
   - Delete companies you don't need
   - Add your company names
   - Keep the list clean (remove unused entries)

**Example:**
```
Your Company Pvt Ltd
Your Company Manufacturing Unit
Your Company Sales Office
```

---

#### **Step 3: Set Up Your Vendors**
1. In the same **"Validation"** sheet
2. Go to **"Vendor Name"** column (Column B)
3. **Default vendors include:**
   - Orion TradeCorp
   - NovaEdge Solutions
   - AquaLeaf Drinks

4. **Add YOUR vendors:**
```
Amazon Business
Office Depot India
Local Stationery Mart
ABC Medical Supplies
XYZ Housekeeping Solutions
```

---

#### **Step 4: Configure Expense Types**
1. Still in **"Validation"** sheet
2. Find **"Exp Type"** column (Column C)
3. **Default categories:**
   - Coffee Material
   - HK Material (Housekeeping)
   - Stationery Material
   - Medicine Material

4. **Customize to your needs:**
```
Office Supplies
IT Equipment
Furniture
Pantry Items
Cleaning Materials
Safety Equipment
```

---

#### **Step 5: Add Manager Names**
1. **"Validation"** sheet → **"Name of the Manager"** column (Column D)
2. **Default managers:**
   - Vikas Patil
   - Ankit Sharma
   - Sneha Iyer
   - Rohit Kulkarni
   - Priya Deshpande

3. **Replace with YOUR managers/approvers:**
```
Rajesh Kumar (Operations Manager)
Priya Sharma (Finance Head)
Amit Patel (Admin Manager)
Sneha Gupta (HR Manager)
```

---

#### **Step 6: Set Up Departments**
1. **"Validation"** sheet → **"Project / Department"** column (Column E)
2. **Default departments:**
   - Administration Dept
   - Finance Dept
   - Human Resources
   - IT Operations
   - Procurement Dept

3. **Add YOUR departments:**
```
Sales & Marketing
Production
Quality Control
Research & Development
Customer Service
Logistics
```

---

#### **Step 7: Configure Employee Lists**
1. **"Requested By"** column (Column F) - Employees who can request
2. **"Authorised By"** column (Column G) - Senior approvers
3. **"Received By"** column (Column H) - Who receives materials

**Add all relevant employees from your organization**

---

### 📝 PART 2: Daily Usage - Creating Purchase Requisitions

#### **Step 1: Enter Requisition Data**

1. Open the **"Data"** sheet (second tab)
2. **Go to the next empty row** (Row 4, 5, 6, etc.)
3. **Fill in the following columns:**

**Column-by-Column Guide:**

| Column | Header | What to Enter | Example |
|--------|--------|---------------|---------|
| A | Sr. No. | Sequential number | 2, 3, 4, 5... |
| B | Duplication Checking | Type "No" (system checks automatically) | No |
| C | Company Name | Select from dropdown | UrbanDesk Workspaces |
| D | Requisition Number | Auto-format: Admin/PUNE/MM/YY-YY/MAT-XX | Admin/PUNE/06/25-26/MAT-02 |
| E | Date (DD-MM-YYYY) | Enter date as DD-MM-YYYY | 10-06-2025 |
| F | Name of the Manager | Select from dropdown | Vikas Patil |
| G | Project / Department | Select from dropdown | Administration Dept |
| H | Requested By | Select from dropdown | Jesika Mehta |
| I | Authorised By | Select from dropdown | Amit Khanna |
| J | Vendor Name | Select from dropdown | NovaEdge Solutions |
| K | Exp Type | Select expense type | HK Material |

---

**Example Entry:**
```
Sr. No.: 12
Duplication: No
Company: UrbanDesk Workspaces
Req. Number: Admin/PUNE/06/25-26/MAT-02
Date: 02-06-2025
Manager: Vikas Patil
Department: Administration Dept
Requested By: Jesika Mehta
Authorised By: Amit Khanna
Vendor: NovaEdge Solutions
Expense Type: HK Material
```

4. **System automatically checks for duplicates!**
   - If you're ordering the same material type in the same month
   - Column B will show **"Its Duplicate"**
   - Review before proceeding

---

#### **Step 2: Generate the Requisition Form**

1. Go to **"Requisition Form"** sheet (first tab)
2. **At the top right**, you'll see: **"Select Sr. [  ]"**
3. **Type the Sr. No.** from your data entry (e.g., 12)
4. Press **Enter**
5. **The form automatically populates** with:
   - Company name (UrbanDesk Workspaces)
   - Requisition number
   - Date
   - Manager name
   - Department
   - Requested by
   - Justification (auto-generated from expense type + month/year)

**Example Auto-Generated Justification:**
```
"NovaEdge Solutions HK Material Order month of June -2025"
```

---

#### **Step 3: Add Item Details to the Form**

Still on the **"Requisition Form"** sheet:

1. **In the items table**, add your materials:

| No. | Description | Lock Code | Unit Price | Qty. | Discount | Total |
|-----|-------------|-----------|------------|------|----------|-------|
| 1 | Cleaning Liquid | CL-001 | ₹150 | 10 | 5% | ₹1,425 |
| 2 | Floor Mops | FM-005 | ₹200 | 5 | 0% | ₹1,000 |
| 3 | Toilet Cleaner | TC-002 | ₹120 | 20 | 10% | ₹2,160 |

2. **Total is calculated automatically** at the bottom right
   - Example: **Rs. 51,826.00** (shown in your form)

---

#### **Step 4: Review and Print**

1. **Review all details** on the form:
   - Company name ✓
   - Requisition number ✓
   - Date ✓
   - Manager/Department ✓
   - Items and total ✓
   - Signature fields ✓

2. **Print the form:**
   - Press **Ctrl + P** (or File → Print)
   - No need to adjust anything!
   - Form is already perfectly formatted
   - Prints on one clean page

3. **Get physical signatures:**
   - Prepared By: (Person who created the form)
   - Approved By: (Manager - Vikas Patil)
   - Authorised By: (Executive - Amit Khanna)

4. **Submit for approval workflow**

---

### 📊 PART 3: Managing & Tracking Requisitions

#### **View All Requisitions**

1. Open **"Data"** sheet
2. This is your **complete requisition database**
3. **Every requisition** ever created is listed here

**You can:**
- **Filter by Company**: See only "UrbanDesk Workspaces" requisitions
- **Filter by Date**: See all June 2025 requisitions
- **Filter by Department**: See all "Administration Dept" orders
- **Filter by Vendor**: See all orders from "NovaEdge Solutions"
- **Filter by Expense Type**: See all "HK Material" purchases

---

#### **Check for Duplicates**

1. In **"Data"** sheet, look at **Column B** (Duplication Checking)
2. **Possible values:**
   - **"No"**: Not a duplicate, safe to proceed
   - **"Its Duplicate"**: This material was ordered recently!

3. **If duplicate detected:**
   - Check the previous entry (same material/company/month)
   - Decide: Is this intentional? Or can we combine orders?
   - Prevent wasteful duplicate purchases

---

#### **Generate Reports**

**Monthly Procurement Report:**
1. Go to **"Data"** sheet
2. Apply filter: Date range (01-06-2025 to 30-06-2025)
3. See all June requisitions
4. Copy to new sheet for analysis

**Vendor-wise Report:**
1. Filter by Vendor Name
2. See total spent with each vendor
3. Use for vendor negotiation

**Department-wise Report:**
1. Filter by Department
2. Track which departments are spending most
3. Budget allocation insights

---

### 💡 PART 4: Pro Tips & Best Practices

#### **Requisition Numbering Best Practices:**

**Format**: `Admin/PUNE/MM/YY-YY/MAT-XX`

- **Admin**: Department code (Admin, Finance, IT, HR)
- **PUNE**: Location code (PUNE, MUMBAI, DELHI)
- **MM/YY-YY**: Month/Financial Year (06/25-26 = June 2025-2026)
- **MAT-XX**: Sequential (MAT-01, MAT-02, MAT-03...)

**Example Numbering:**
```
Admin/PUNE/06/25-26/MAT-01  (First admin requisition in June)
Finance/MUMBAI/06/25-26/MAT-01  (First finance req in Mumbai)
IT/PUNE/07/25-26/MAT-01  (First IT requisition in July)
```

---

#### **Avoiding Common Mistakes:**

❌ **Don't skip the Sr. No.** - Always use sequential numbers  
❌ **Don't enter wrong date format** - Must be DD-MM-YYYY  
❌ **Don't ignore duplicate warnings** - They save money!  
❌ **Don't modify formulas** in the Requisition Form sheet  
❌ **Don't delete validation data** - Breaks the dropdown menus  
❌ **Don't skip signature collection** - Needed for audit trail  

---

#### **Approval Workflow Tips:**

1. **Prepare the form completely** before sending for approval
2. **Attach supporting documents** (quotations, purchase justification)
3. **Follow hierarchy**:
   - First: Requestor prepares
   - Second: Manager approves
   - Third: Executive authorizes
4. **Keep copies**: Print 2 copies (one for records, one for purchase team)
5. **Track status**: Mark as "Pending", "Approved", "Rejected" in notes

---

#### **Vendor Management Tips:**

- **Update vendor list regularly** when new vendors are approved
- **Remove inactive vendors** to keep list clean
- **Add vendor contact info** in a separate tracking sheet
- **Rate vendors** based on delivery time, quality, pricing

---

#### **Multi-Company Usage:**

If managing multiple companies:
1. **Color-code** each company in Excel (conditional formatting)
2. **Create separate reports** per company monthly
3. **Set up approval hierarchies** per company
4. **Track budgets** separately for each company

---

### 🔧 PART 5: Customization & Advanced Features

#### **Adding Your Company Logo**

1. Go to **"Requisition Form"** sheet
2. Click on the top-left area (where logo would go)
3. Insert → Pictures → Select your company logo
4. Resize to fit (approx. 2cm x 2cm)
5. Logo will print on every requisition

---

#### **Customizing the Form Layout**

You can modify (if you know Excel):
- **Colors**: Change blue headers to your brand color
- **Font**: Change to your corporate font
- **Add fields**: Extra approval levels, project codes
- **Remove fields**: Unused sections

**Important**: Don't modify cells with formulas!

---

#### **Creating Additional Expense Categories**

1. **"Validation"** sheet → Column C
2. Add new expense types:
```
Safety Equipment
IT Hardware
Furniture & Fixtures
Marketing Materials
Travel Expenses
```

3. These will automatically appear in dropdown menus

---

#### **Setting Up Location-Based Numbering**

If you have multiple offices:

1. Change requisition number format to include location:
   - `Admin/PUNE/06/25-26/MAT-01`
   - `Admin/MUMBAI/06/25-26/MAT-01`
   - `Admin/DELHI/06/25-26/MAT-01`

2. Each location maintains separate sequential numbering

---

#### **Integrating with Purchase Order System**

After requisition is approved:
1. **Copy requisition data** to Purchase Order sheet
2. **Generate PO number** based on requisition
3. **Link both documents** for tracking
4. **Close loop** when material is received

---

#### **Adding Budget Tracking**

Create a new column in "Data" sheet:
- **Budget Code**: Which budget this draws from
- **Budget Remaining**: How much left in that budget
- **Alert if over budget**: Conditional formatting

---

## 📊 Technical Implementation

**Technology Stack:**
- Microsoft Excel (Advanced formulas and data validation)
- VLOOKUP/XLOOKUP for form auto-population
- Data Validation for dropdown menus
- Conditional Formatting for duplicate alerts
- Named Ranges for dynamic dropdowns
- Print area optimization for professional output

**Data Structure:**
```
Purchase Requisition System
├── Requisition Form (Print-ready form)
│   ├── Company header
│   ├── Requisition details
│   ├── Item details table
│   └── Signature sections
├── Data (Master database)
│   ├── All requisition entries
│   ├── Duplicate checking column
│   └── Complete tracking information
└── Validation (Master lists)
    ├── Company names
    ├── Vendor names
    ├── Expense types
    ├── Manager names
    ├── Departments
    ├── Requested by (employees)
    ├── Authorised by (executives)
    └── Received by (receivers)
```

**Key Formulas:**
```excel
Duplicate Detection: IF(COUNTIFS(Company,ThisCompany,ExpType,ThisExpType,Month,ThisMonth)>1,"Its Duplicate","No")
Form Population: VLOOKUP(SelectedSr,DataRange,ColumnNumber,FALSE)
Auto-Justification: VendorName & " " & ExpType & " Order month of " & MonthYear
Total Calculation: SUM(Qty * UnitPrice * (1-Discount%))
```

## 💡 Business Benefits

✅ **Time Savings**: 10-minute requisition vs. 30-minute manual form  
✅ **Prevents Duplicates**: Auto-detection saves money on redundant orders  
✅ **Audit Trail**: Complete history of all requisitions  
✅ **Approval Clarity**: Clear workflow with signature tracking  
✅ **Multi-Company**: Manage all entities in one system  
✅ **Data Consistency**: Validation ensures clean data  
✅ **Professional Output**: Print-ready forms every time  
✅ **Easy Reporting**: Filter and analyze procurement patterns  

## 📈 Future Enhancements

Planned improvements:
- [ ] Web-based version (no Excel needed)
- [ ] Mobile app for quick requisition requests
- [ ] Email notifications for approval workflow
- [ ] Integration with accounting systems
- [ ] Automatic PO generation from approved requisitions
- [ ] Budget integration and alerts
- [ ] Vendor rating and performance tracking
- [ ] Material receipt tracking
- [ ] Invoice matching against requisitions
- [ ] Advanced analytics dashboard

## 💼 For Freelancers & Employers

**Skills Demonstrated:**
- Procurement process automation
- Excel advanced formulas (VLOOKUP, COUNTIFS, data validation)
- Business process design
- Multi-entity management
- Duplicate detection logic
- Print optimization and formatting
- Data consistency and validation
- Approval workflow design

**This project shows:**
- Understanding of procurement operations
- Attention to process efficiency
- Data integrity focus (duplicate prevention)
- Professional documentation skills
- Scalable system design

**Available for:**
- Custom procurement systems
- Purchase order automation
- Vendor management solutions
- Approval workflow tools
- Excel-based business applications
- Process optimization consulting

## 🤝 Contributing & Feedback

This system can be customized for various industries:
- Manufacturing companies
- Service organizations
- Educational institutions
- Healthcare facilities
- Retail businesses

If you have suggestions or need customization, feel free to reach out!

## 📞 Contact

For customization requests, freelance work, or questions:
- [**GitHub**](https://github.com/heysubu)
- **Email**: suubhamghadge@gmail.com
- [**LinkedIn**](https://www.linkedin.com/in/subhamghadge/)

## 📄 License

This project is available under the MIT License - use and modify for your organization's needs.

---

### 🌟 Project Stats

![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoft-excel)
![Procurement](https://img.shields.io/badge/Procurement-Management-blue)
![Automation](https://img.shields.io/badge/Automation-High-success)
![Multi--Company](https://img.shields.io/badge/Multi--Company-Support-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

**📋 Streamline Your Procurement - From Request to Approval in Minutes**

**⭐ If this system helps your organization, please star this repository!**

**💬 Have questions? Open an issue and I'll assist you!**

**🎯 Start managing requisitions efficiently today!**
