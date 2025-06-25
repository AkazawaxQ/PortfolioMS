# 📊 Portfolio Management System (PMS)

This is a Windows Forms application for managing investment portfolios, assets, wallet balance, and reports.

## 💾 Database

SQL scripts are inside the `/SQL` folder:
- `PMSTables Finalized`: Database schema
- `PMSViews Finalized` : Views of Tables
- `PMSStoredProcedures` Finalized: Stored Procedures
- `PMSUDFS Finalized` : User Defined Functions
- `PMSTriggers Finalized` : Triggers
- `PMSAdminKey after Tables` : Admin key will be needed in register form, in order to create an admin account
- `PMSMarketDataSeed Finalized` : Seed Data for Market
- `PMSIndexes Finalized` : Index adjustments

## 🔧 Tech Stack

- C# WinForms (.NET Framework)
- Microsoft SQL Server

## Notes
- In order to use this application, you need to change SQL connection strings within Visual Studio codes, after setting your connection string, it is completely executable.
- And also there are 2 UDFs exist that one of it "MarketPriceSimulation" and other one is "Backup", you can add them to SQL Server Agent and create daily jobs, it will increase the user experience.
