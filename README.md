POSNext Documentation

Update Note

We have introduced an upgraded branch (Version 15) for POSNext, fully compatible with both ERPNext Version 14 and ERPNext Version 15. In this update, the POS Invoice step has been streamlined, and invoices are now created directly within the Sales Invoice module, enhancing efficiency and simplifying the workflow.

Introduction

POSNext is an open-source Point of Sale (POS) system designed specifically for ERPNext. It is a fork of the default ERPNext POS, enriched with additional features inspired by POSAwesome and further innovations to meet the demands of modern retail and business environments. POSNext serves as a flexible, customizable alternative to POSAwesome, offering users improved adaptability and enhanced functionalities.

Getting Started

POSNext is integrated with ERPNext’s default POS module. To begin using POSNext, ensure you have an active installation of ERPNext.

Prerequisites

A running instance of ERPNext Version 15 or 14

Setting Up POSNext

Installation:

Available on Frappe Cloud Marketplace.

Configuration:

Access POS Profile Settings: Navigate to the POS Profile settings within ERPNext.

Configure Basic Settings: Set up essential configurations such as currency, default warehouse, and user-specific settings.

Assign User Roles and Permissions: Define user roles and permissions tailored to POS operations, ensuring access control and security.

Full Compatibility with ERPNext POS Features: POSNext retains all core ERPNext POS features, ensuring seamless integration with existing functionalities.

Profile Lock in POS Settings: This option makes POS settings read-only, preventing unauthorized changes and maintaining configuration integrity.

Show Order List Button: Adds an "Order List" button in POS, allowing users to conveniently view all orders from within the POS interface.

Show Held Button: Displays a "Held" button in POS, enabling users to temporarily place orders on hold for later completion.

Mobile Number-Based Customer Identification: This feature locks the customer field and uses mobile numbers to identify customers, simplifying customer selection and ensuring accuracy.

Show Checkout Button: Adds a "Checkout" button, allowing users to finalize transactions with ease and improving the checkout process.

Show Only List View: Limits the POS interface to a streamlined "List View," displaying item details in an organized list format.

Show Only Card View: Configures the POS interface to display items exclusively in "Card View," enhancing visual selection with a card layout.

Show Open Form View: An optional feature in the POS menu to open a detailed form view, offering an expanded item and transaction detail view.

Show Toggle for Recent Orders: Enables a toggle within POS for a list of recent orders, providing quick access to previous transactions for reference.

Save as Draft Option: Allows users to save orders as drafts, offering flexibility for later review or editing.

Close POS Option: Adds an option in the POS menu to close the POS interface, supporting session management and security.

Default View Setting (Card/List): Sets either Card View or List View as the default display mode, allowing users to choose their preferred layout.

Allow Adding New Items on Separate Lines: Allows users to add new items on individual lines in POS, helping in item organization and clarity.

Display Posting Date: Shows the transaction posting date in POS, enhancing transparency and record-keeping accuracy.

Show OEM Part Number: Displays the Original Equipment Manufacturer (OEM) part number on items in POS, aiding in quick and accurate item identification.

Show Logical Rack Location: Displays the logical rack location of items in POS, assisting in efficient item retrieval and inventory management.

Edit Rate and UOM (Unit of Measure): Allows direct modification of item rates and UOMs, providing flexibility in pricing and measurement.

Enable Credit Sales: Supports credit sales in POS, enabling transactions on credit terms when required.

Add Additional Notes: Provides an option to add transaction-specific comments or instructions in POS, enhancing communication within sales records.

Include and Exclude Tax Options: Offers the ability to include or exclude tax from the final amount, adapting to different transaction and customer needs.

Display Alternative Items for POS Search: Shows alternative items during searches in POS, helping users find substitutes for out-of-stock items. Alternative items should be listed in the main item's "Alternative Items" table.

Configure Mobile Number Length: Sets mobile number length according to country specifications, ensuring proper format and validation.

Send Invoice via WhatsApp: Enables sending invoices through WhatsApp to customers identified by mobile numbers, providing a quick and convenient digital invoicing solution.

Customizable POS Profile for Diverse Operations: Allows for tailored profile adjustments within POS to support specific operational needs, such as handling multi-currency transactions and other business-specific requirements.

Credit Sale: Enables POS users to process credit sales, allowing customers to make purchases on credit terms, which is recorded for future payment tracking.

Incoming Rate: Tracks the cost at which items are received or procured

This documentation provides a comprehensive overview of POSNext’s features and functionalities, guiding users through setup, configuration, and key capabilities that support efficient POS management within ERPNext.
