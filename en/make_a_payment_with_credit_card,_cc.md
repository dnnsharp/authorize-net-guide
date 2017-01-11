## Make a payment with Credit Card, CC

### Intro

This type of payment allows one to make a payment with Credit Card through Authorize.Net's Payment Gateway, using Authorize.Net's Advanced Integration Method \(AIM\).

The security of an AIM transaction is ensured through a 128-bit Secure Sockets Layer \(SSL\) connection between the merchant’s Web server and the Authorize.Net Payment Gateway.

There are different credit card transaction types supported by the payment gateway and they each have specific field requirements: 

* Authorization and Capture; 
* Authorization Only; 
* Prior Authorization and Capture, etc.

Make sure you have already read the Authorize.Net manual prior to using different credit card transaction types and specific fields: [http://www.authorize.net/support/AIM\_guide.pdf](http://www.authorize.net/support/AIM_guide.pdf). 

For your convenience, DNN Authorize.Net Add-on already contains a template available in ActionForm to get you started, called '

Pay With Credit Card, Authorize.Net.It is a form that will do an Authorization and Capture transaction. This is the most common type of credit card transaction and is the default payment gateway transaction type. The amount is sent for authorization, and if approved, is automatically submitted for settlement.

### Requirements

* The merchant must have a merchant bank account that allows Internet transactions.

* The merchant must have an e-commerce \(Card Not Present\) Authorize.Net Payment Gateway account.

* The merchant must have a valid Secure Sockets Layer \(SSL\) certificate and their Web site must be capable of initiating both client- and server-side SSL connections.

* The merchant must be able to store payment gateway account data securely \(for example, API Login ID, or Transaction Key\).

* The merchant must have one of the following module installed

  * Action Form 03.08.74

  * Action Grid 04.00.39

  * DNN API Endpoint 01.02.15

  * Sharp Scheduler 02.01.18

  * InfoBox 01.01.22

* The merchant must have a platform containing DNN 6 and ASP.NET 4.0 at the least.

### Getting started



