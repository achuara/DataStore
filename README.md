# DataStore
# file-based key-value data store that supports the basic CRD (create, read, and delete) operations.


# output

=============================================================
========================CREATE ==============================
=============================================================
Create operation successful
Operation failed due to key already available
Operation failed due to key already available
Create operation successful
Operation failed due to key length exceeded the limit(32chars)
====================AFTER WAIT===============
Create operation successful
Operation failed due to key already available
Operation failed due to key already available
Operation failed due to key already available
=============================================================
==========================READ===============================
=============================================================
{"firstName":"John","lastName":"Britto","address":"Chennai","age":"25"}
{"firstName":"John","lastName":"Britto","address":"Chennai"}
Operation failed due to key not available
Operation failed due to key length exceeded the limit(32chars)
====================AFTER WAIT===============
Operation failed due to key not available
{"firstName":"John","lastName":"Britto","address":"Chennai"}
=============================================================
========================DELETE ==============================
=============================================================
Operation failed due to key not available
Record deletion successful
Operation failed due to key not available
Operation failed due to key not available
Operation failed due to key length exceeded the limit(32chars)
