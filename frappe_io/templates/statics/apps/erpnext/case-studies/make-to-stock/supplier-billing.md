# Supplier Billing

### Purchase Invoice

Depending on the payment terms, Purchase Invoice is either made on Purchase Order or on receipt of materials. If your supplier's billing is linked to receipts, then make the Purchase Invoice from Purchase Receipt, else make it from Purchase Order.

#### Figure 1: Make Purchase Invoice

![Purchase Invoice](assets/frappe_io/images/erpnext/m-t-s-purchase-invoice.png)

Payment Entry is done to book all accounting transactions in your system. It is an important step of Book Keeping.

#### Double Entry Accounting

Double entry bookkeeping is a system of accounting in which every transaction has a corresponding positive and negative entry : debits and credits. Every transaction involves a debit entry in one account and a credit entry in another account. This means that every transaction must be recorded in two accounts; one account will be debited because it receives value and the other account will be credited because it has given value. ERPNext follows the Double Entry Accounting method.

Payment Entry is done after you click on the button Make Payment Entry. The entries will be done by the system. However, it is necessary that you click on the button ‘Make Difference Entry’. This step will calculate the Total Debt and the Total Credit.

#### Figure 2: Make Payment Entry

![Payment Entry](assets/frappe_io/images/erpnext/m-t-s-payment-entry.png)

In case for some reason, the account section is blank, it means that you have not selected your default bank account. If you have confusion on where to post what, click on the triangle button next to the Company to set the default master account.

#### Figure 3: Go to Masters (Optional: In case defaults not set)

![Default setting](/assets/frappe_io/images/erpnext/triangle-button-company.png)

The click will take you to the Master-Company file. Now enter your default entry account as HDFC Bank/Axis Bank etc and Save. This will enable the system to post debit/credit entries directly against this particular account.

After completing the Purchase cycle, go and make the Production Order.
