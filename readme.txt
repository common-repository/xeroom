=== Xeroom ===
Contributors: palloyd
Tags:  Xero, woocommerce xero link, Woo, woocommerce xero integration, WooCommerce, invoice, Xeroom, stock management, accounting integration, account synch, orders synch
Requires at least: 4.4
Tested up to: 4.9
Requires PHP:5.6
Requires WooCommerce: 3.3.3
Requires ioncube loader 10.2
Stable tag: trunk
Version: 2.0.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Xeroom will intelligently push WooCommerce orders and payments into Xero to automatically create sales invoices, credit notes and inventory changes saving hours of reentering data.
 
== Description ==
 
Xeroom is an extension of WooCommerce that will take the sales orders and post them to the Xero online accounting application creating sales invoices. 

1. Posts transactions intelligently into the correct accounts in xero.
2. Passes customer name and address details, order lines, shipping, prices, sales taxes, discounts, coupons, product SKU codes, descriptions, inventory, references and payments to Xero.
3. Generates credit notes in Xero for order refunds in Woo.
4. Inventory check and update both ways when sku ordered.
5. Post sales into different product and geography accounts in Xero to provide value added reporting in Xero.
6. Post shipping charges to a separate Xero account.
7. Choice of Xero or WooCommerce as Master for invoice data.
8. Ability to post individual orders from WooCommerce order screen with one-click button - useful for telephone orders.
9. Bulk posting of historic orders - for new installations or migrations.
10. Set sales tax methods to apply in Xero. (Standard, reduced and zero tax rates for different geographies and products in next release.)
11. Set Autocomplete to post automatically on completion of checkout payment.
12. Full control over the status of created invoices in Xero - ie draft, unpaid or paid.
13. Post payments to different Xero bank accounts according to the checkouts used in WooCommerce.


Xeroom provides far more functionality than currently exists on other similar plugins providing intelligent posting of transactions into Xero's accounts rather than just a flat memo dump of the order thus allowing proper analysis and audit trails.  It is available as both a free version and paid for Premium version.  

== Download ==

Please download from our website https://www.xeroom.com/support/

 
== Installation Procedure ==

For the full step-by-step procudure please go to the installation page on our site.

If you don't have the time or need help with this we can do the install setup and test for you for just $97. 

 
== Frequently Asked Questions ==
 
= Is Xeroom free? =
 
Yes we provide a free version as well as a Premium lifetime licenced version for just $97.  The free version performs all of the premium version functions apart from inventory.  It also has a line on the invoice in Xero stating produced by free version of Xeroom.  The Premium version is available with annual or lifetime support including free updates.  Installation is available as an option as is setup and configuration of your Xero accounts and WooCommerce.
 
= Why do I need a xero.com application? =
 
The Xero application is essential in order to provide the api consumer key and api consumer security keys without which the xeroom plugin cannot work. This enables secure and correct communications to take place between your on-line Xero account and your Woocommerce site.
 
= I already have a xero account, What's next I need to do? =
 
Follow the detailed installation procedure here https://www.xeroom.com/installation-instructions/.

= Where do I find more information about Xeroom? =

Go to our website www.xeroom.com which maintains the latest information.
 
== Screenshots ==
 
1. Dashboard.
2. Settings.
3. Product settings.
4. Geography settings.
5. Debug screen.
6. Bulk export dashboard.
7. Order processing.
8. Credit note generation.
9. Xero invoice.
10. Sales Tax Settings
11. Checkout Payment Methods.

== Changelog ==
 
= 1.1 =
Release date: November 2015, initial stable release

= 1.2 =
Release date: January 2016, enhancements to inventory synch

= 1.3 =
Release date: March 11th, 2016 enhancements and bug fixes

= 1.4.1 =
Release date: December 18th, 2016  bug fixes and sales tax account bug fix

= 1.5.2 =
Release date: May 19th, 2017  

Bug fixes:

1. Header issue - on some servers this bug prevented the order process from completing.
2. Licence key – was randomly dropping.
3. Free version product codes – were not copied across or synched with Xero correctly.
4. Free version bank account setting - was not recognised and so no completion possible. 
5. Free version tax account not updating - if changed or creating in Xero if not exist.

Enhancements:

1. Upgraded to work with Version 3.06 of Woocommerce.  Earlier versions are no longer supported.
2. Products can now be held inclusive or exclusive of GST/VAT/Sales tax in Woo.  An option is added in the settings to set this. By default prices are received by Xero and treated as tax exclusive with whatever GST tax specified in Xero or copied across then added by Xero.  Some customers want to keep their prices in Woo as tax inclusive and so when it was sent to Xero the tax was added again resulting in incorrect tax. Now this is possible. 
3. Settings saved – if Xeroom is uninstalled and then reinstalled the settings are now remembered and repopulated.
4. Before Sale product prices – these are now added as a suffice to the product description so the invoice in Xero shows both the full (before sale) and the sale prices.


= 1.6.0=
Release date: November 18th, 2017

Bulk Data Load Version released.  This powerful tool enables an unlimited number of historic orders to be posted to Xero in one go which makes it ideal for customers who are migrating to Xero and want to bring their history with them for the current financial year.  You can post all orders or a selection and also choose whether to post each one as a Paid or Unpaid invoice.


= 2.0.0 =
Release date: March 22nd, 2018  

Enhancements: Major release with ability to:

1. Post sales into separate product category accounts in Xero.
2. Post sales into separate accounts according to geographic zones & regions
3. Create invoices as draft status in Xero.
4. Post shipping revenues/charges to a separate sales account in Xero.
5. Generate credit notes for cancelled orders.
6. Repost payments for any failed orders.
7. Post orders and payments from the WooCommerce admin screen back-end.
8. Notes added to the order when posted to Xero or order cancellations and credit notes made.
9. Increased security of code to new WP standards.
10. Enforced security use of TPS1.2 communications protocol for Xero
11. Various bug fixes.
12. Encrypted code using ioncube for greater security and virus protection.

= 2.0.4 =
Release date: July 18th, 2018 

1. Sales taxes VAT/GST - Full flexibility to map WooCommerce standard, reduced and zero rate taxes into Xero tax methods so that Xero can calculate and post sales taxes flexibly with the same or different rates.  
2. Multiple checkouts - different checkouts can be posted to different Xero accounts.
3. Xero API connection status indicator added.
4. Fees added to WooCommerce orders in the backend now posted to Xero.
5. Show Xeroom licence key.
6. Wholesale prices plugin compatability.
7. Product sales breakout accounts by geography or category increased to 25.
8. Tested to Woocommerce 3.4.3 and WordPress 4.9.7

Bug fixes:

1. Xero product description overwriting bug.
2. Screen flicker when loading Xeroom pages. 
3. Invalid product error on checkout with variable products.

== Planned Enhancements ==
= 2.0.5 =
Release date:  Sept, 2018

1. Separate Stripe and other card payment fees to separate account.
2. Rounding error handling to separate account.
3. Automatically email customers Xero invoices when the order completes.
4. Full inventory synch in real-time or on a schedule.

