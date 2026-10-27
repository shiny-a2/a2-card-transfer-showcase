# Bank-transfer payment review

A bank-transfer checkout needs more than an account number. Customers need a clear place to submit a receipt, and staff need to distinguish a submitted receipt from a confirmed payment.

This WooCommerce module separates account validation, customer instructions, receipt storage and administrator review. It validates bank details before displaying them, keeps uploaded receipts out of public media storage, and records review actions. Payment limits remain a store setting rather than a loyalty rule.

The source was preserved in a private repository after a history scan. Ten local PHP suites passed, covering 539 assertions across account validation, receipts, customer and administrator behavior, gateway loading, records and settings. Those results do not establish a live bank settlement or a successful production checkout.

This repository contains an implementation summary only. Production source, bank details, receipt images and customer records remain private.
