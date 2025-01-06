# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is used to increment or decrement a numeric field. However, in this case, a string value ('1') is passed, leading to an error.

**Bug:**
The provided code snippet attempts to increment the `counter` field by '1', which is a string, causing an error. The correct approach is to use a numeric value.

**Solution:**
The solution modifies the code to use the numeric value 1 instead of the string '1', fixing the error.
