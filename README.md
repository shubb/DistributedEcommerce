# DistributedEcommerce

Initially an architecture excersise. 

A set of applications for running a buisness that sells products online and through an app, and delivers them in real time via a network of couriours.

Real time delivery is hard, because it requires a network of warehouses and delivery drivers. However, in every city this already exists in the form of takewaway food shops. Many shops are open 24/7 and would be happy to hold a small amount of stock, picking and delivering it using under utilised drivers. This set of applications provides an ordering and distributed stock management and delivery system. 

Components:
* Front End
** Ecomerce Platform - 
*** Cross platform app
*** Web application
*** Shared components (the majority of views and logic can be shared)
** Stock management
** Driver Cross Platform Application
** Distributor Delivery Alert Web Application
** Distribtor Stock Communication Web Application
*** Distributor Registration / Management app
** QRScanner Shared Component
* Back End
** Distributor Registration
** StockAssigner - Assign stock to a distributor
** StockSelector - List stock available for delivery to a specific location
** StockPicker - Find the best ditributor to service an order
** StockResolver - Remove stock from a given distributor
** QRToStock - Find the stock uuid for a given item
** SKUData - Returns the ecomerce data for a given SKU

MVP:
* Ecomerce App
* Driver App

