# DataStore
# file-based key-value data store that supports the basic create, read, and delete operations.


# output

 #                     CREATE 
#Create operation successful
#Operation failed due to key already available
#Operation failed due to key already available
#Create operation successful
#Operation failed due to key length exceeded the limit(32chars)
 #                  AFTER WAIT
#Create operation successful
#Operation failed due to key already available
#Operation failed due to key already available
#Operation failed due to key already available
 #                      READ
#{"firstName":"suman","lastName":"kumar","address":"punjab","age":"23"}
#{"firstName":"saman","lastName":"kumar","address":"punjab"}
#Operation failed due to key not available
#Operation failed due to key length exceeded the limit(32chars)
 #                    AFTER WAIT
#Operation failed due to key not available
#{"firstName":"suman","lastName":"kumar","address":"punjab"}
 #                      DELETE
#Operation failed due to key not available
#Record deletion successful
#Operation failed due to key not available
#Operation failed due to key not available
#Operation failed due to key length exceeded the limit(32chars)
