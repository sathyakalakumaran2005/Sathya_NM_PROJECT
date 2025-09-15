# Sathya_NM_PROJECT
A ServiceNow-based project for managing family expenses by automating data entry, linking tables, and generating real-time expense records. Developed as part of the Naan Mudhalvan initiative, this project helps maintain accurate daily expenditure records using tables, relationships, business rules, and workflows in ServiceNow.
README.md

# Calculating Family Expenses Using ServiceNow

## Project Overview
This project, developed under the **Naan Mudhalvan Initiative**, focuses on creating a **ServiceNow-based solution** for managing daily family expenses. Traditionally, families maintain expense records in notebooks or notes, which can be easily misplaced or become disorganized.  
This solution automates expense tracking using **ServiceNow tables, relationships, business rules, and flow designers** to streamline data entry and calculations.

---

## Objectives
- Design a centralized system to manage family expenses in ServiceNow.
- Automate expense calculations and maintain organized records.
- Reduce manual work and minimize errors in expense management.
- Create scalable solutions with the potential for future enhancements like reports and dashboards.

---

## Team Details
- **Team ID:** NM2025TMID15476  
- **Team Leader:** Sathya Kala K  
- **Team Members:** Aswini B, Jemima A, Meena M  

---

## Skills & Tools Used
- **ServiceNow Basics**
- **Tables & Relationships**
- **Update Sets**
- **Business Rules**
- **Flow Designer**

---

## Project Implementation

### **Milestones Completed**
1. **Setting Up ServiceNow Instance**
   - Created a personal developer instance on ServiceNow.
   
2. **Creation of Update Set**
   - Created and configured a new update set: *Family Expenses*.

3. **Creation of Tables**
   - **Family Expenses Table**: Stores daily expense totals.
   - **Daily Expenses Table**: Maintains individual expense details.

4. **Auto Numbering & Form Design**
   - Configured auto-generated numbers for each record.
   - Customized forms with mandatory fields and read-only properties.

5. **Relationships & Related Lists**
   - Linked *Daily Expenses* with *Family Expenses* tables.
   - Added *Daily Expenses* as a related list to the *Family Expenses* table.

6. **Business Rules**
   - Automated updating of total expenses and expense details.

7. **Flow Designer**
   - Configured flow to refine expense queries between related tables.

---

## Project Structure

ServiceNow Project │ ├── Family Expenses Table │   ├── Columns: Number, Date, Amount, Expense Details │   └── Business Rules for Automated Updates │ ├── Daily Expenses Table │   ├── Columns: Number, Date, Expense, Family Member Name, Comments │   └── Relationship with Family Expenses │ └── Flow Designer Scripts & Relationships

---

## Future Enhancements
- Expense reports and charts  
- Mobile-friendly UI for quick expense entry  
- Data analytics and insights for better expense planning  

---

## Conclusion
This project demonstrates how **ServiceNow** can be used beyond enterprise use cases, even for simple personal applications like **family expense management**. It automates data entry, calculations, and reporting, making expense management efficient and error-free.

---

## License
This project is developed for educational purposes under the Naan Mudhalvan Initiative.

