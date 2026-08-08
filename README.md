ArchTech IMS — Client Demo Package
===================================

HOW TO RUN
-----------
Unzip this folder, then open "index.html" in a browser (double-click it,
or drag it into a browser window). No server or internet connection is
required — everything runs locally as static HTML.

LOGIN
-----
  Email:    demo@archtechbd.com
  Password: Demo@2026

These are shown directly on the sign-in screen with an "Autofill &
continue" button, so whoever is running the demo can log straight in
without having to remember or type anything.

WHAT'S NAVIGABLE
-----------------
The sidebar menu now links between all ten built screens, so the client
can click around naturally instead of jumping between separate files:

  - Dashboard            (dashboard.html)
  - Sales History        (sales-history.html)
  - Inventory / Stock     (inventory.html)
  - Customers (CRM)       (customers.html)
  - Dues / Receivables    (dues.html)
  - Purchase Orders       (purchase-orders.html)
  - Reports & Analytics   (reports.html)
  - Taxes & VAT / Invoice (vat-invoice.html)
  - General Settings      (settings.html)
  - Log Out returns to the sign-in screen from any page

Menu items for screens that aren't part of this demo phase (POS/Billing,
Suppliers, User & Role Management, Branches, Payment Methods, System
Logs, Backup & Restore, etc.) are dimmed and show a "Not included in
this demo" tooltip instead of a dead link.

WHAT'S STATIC
-------------
This is a front-end visual demo, not a connected application — the data
on every screen is sample data, and actions like Save, Import, Export,
and Delete are not wired to a real backend (some show a small "demo
only" toast when clicked, which is expected). Page-to-page navigation
and login are fully working for the walkthrough.

FILES
-----
index.html            Sign-in screen (start here)
dashboard.html         Dashboard
sales-history.html     Sales History / Transactions
inventory.html         Inventory / Stock Management
customers.html         Customers (CRM)
dues.html               Customer Dues / Receivables
purchase-orders.html   Purchase Orders
reports.html            Reports & Analytics
vat-invoice.html        VAT / Invoice Detail
settings.html           General Settings
