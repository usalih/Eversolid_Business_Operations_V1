# Eversolid Business Operations — V1

A local-first business operations / lightweight ERP prototype for Eversolid NG Ltd.

## Product direction
Inspired by the connected workflow thinking of ShopLog Pro, but adapted for wholesale, procurement, distribution, project supply, inventory and finance rather than woodworking/maker shops.

## V1 modules
- Dashboard / action centre
- Projects and profitability
- Tasks / kanban
- Calendar
- Deliveries
- Customers
- Quotations
- Sales Orders placeholder
- Invoices
- Payments
- Suppliers
- Purchase Orders
- Goods Received
- Inventory
- Warehouses
- Stock movements / activity trail
- Product catalog
- Income / expenses
- Receivables / payables
- Cash flow
- Business analytics
- Project profitability
- Reports
- Documents / print-ready views
- Global search
- EOD review
- Settings
- JSON backup / restore
- Inventory CSV export

## Technical approach
V1 is intentionally local-first and has no server dependency. Data is persisted in browser localStorage. This is a functional prototype intended for product review and workflow validation, not yet a multi-user production ERP.

The app uses plain HTML/CSS/JavaScript so it can be opened directly or served by any static web server. The architecture is separated into `index.html`, `styles.css`, and `app.js` to make the next backend/API migration easier.

## Demo data
The initial dataset is illustrative. It is not a claim about Eversolid's actual customers, suppliers, revenue, stock, projects or financial records.

## External links
- ShopLog inspiration: https://getshoplog.com/
- Stockeep reference: https://www.stockeep.com/
- Eversolid official website: not linked in V1 because a public official URL could not be verified.

Add the confirmed company URL when one is supplied.

## Running
Open `index.html` in Chrome/Edge/Firefox, or serve the folder through a local static server.
