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
Every page now shares the exact same sidebar (same design, same item
list, same order) so the demo feels like one connected product instead
of separate screens stitched together:

  - Dashboard            (dashboard.html)
  - POS / Billing         (not in this demo)
  - Inventory / Stock     (inventory.html)
  - Purchases             (purchase-orders.html)
  - Sales                 (sales-history.html)
  - Customers (CRM)       (customers.html)
  - Dues / Receivables    (dues.html)
  - Suppliers             (not in this demo)
  - Reports & Analytics   (reports.html)
  - Settings              (settings.html)
      - General Settings  (settings.html)
      - User & Role Mgmt  (not in this demo)
      - Branches          (not in this demo)
      - Taxes & VAT       (vat-invoice.html)
      - Payment Methods   (not in this demo)
      - System Logs       (not in this demo)
      - Backup & Restore  (not in this demo)

The current page is always highlighted in the sidebar. Log Out (from
the top-right profile menu, where present) returns to the sign-in
screen.

Menu items for screens that aren't part of this demo phase are dimmed
and show a "Not included in this demo" tooltip instead of a dead link.

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
