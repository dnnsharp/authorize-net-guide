# Make a payment with Electronic Check

**
Intro**

This type of payment allows one to submit electronic check transactions through an Authorize.Net Card Not Present Payment Gateway account, using Authorize.Net's Advanced Integration Method (AIM).

eCheck.Net® is Authorize.Net’s exclusive electronic check processing solution. eCheck.Net enables Web merchants already processing credit card transactions through the Authorize.Net Payment Gateway to offer their customers an additional payment option.

The security of an AIM transaction is ensured through a 128-bit Secure Sockets Layer (SSL) connection between the merchant’s Web server and the Authorize.Net Payment Gateway.

There are different electronic check transaction types supported by the payment gateway and they each have specific field requirements: Authorization and Capture, Authorization Only, Prior Authorization and Capture, etc.Make sure you already read the Authorize.Net manuals prior to use different electronic check transaction types and specific fields.

There are currently six eCheck.Net transaction types supported by the Authorize.Net Payment Gateway.

* Accounts Receivable Conversion (ARC)

  This transaction type is a one-time charge against a customer's checking account. ARC allows merchants to collect payments received in the mail or left in a drop-box and convert them to an electronic payment.
  
* Back Office Conversion (BOC)
 
  This transaction type is a one-time charge against a customer's checking account. BOC allows merchants to collect a check written at a point of sale (checkout counter, manned bill payment location, service call location) and convert it to an ACH debit during back office processing.

* Cash Concentration or Disbursement (CCD)

  This transaction type is a one-time or recurring charge or refund against a business checking account. CCD transactions are fund transfers to or from a corporate entity.

* Internet-Initiated Entry (WEB)

  This transaction type is a one-time or recurring charge against a consumer checking or savings account and for which payment authorization has been obtained from the customer via the Internet.

* Prearranged Payment and Deposit Entry (PPD)

  This transaction type is a one-time or recurring charge or refund against a consumer checking or savings account. PPD transactions may only be originated when payment and deposit terms between the merchant and the customer are prearranged.

* Telephone-Initiated Entry (TEL)
  
  This transaction type is a one-time charge against a consumer checking or savings account that was originated by telephone. TEL transactions can only be originated when an existing relationship between the merchant and the customer exists; or if no relationship exists, the customer must initiate the telephone call to the merchant.

For your convenience, DNN Authorize.Net Add-on contains four templates to get you started, named: 'Pay With eCheck ARC Authorize.Net', 'Pay With eCheck PPD Authorize.Net', 'Pay With eCheck TEL Authorize.Net' and 'Pay With eCheck WEB Authorize.Net'.

