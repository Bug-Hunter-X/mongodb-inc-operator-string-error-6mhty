# MongoDB $inc operator error with string value
This example demonstrates an uncommon error in MongoDB related to the $inc operator.  The $inc operator is used to increment a numerical field.  However, if a string value is provided instead of a numerical value, an error may occur or the operation might produce unexpected results.

## Bug Description
The bug is caused by providing a string value to the $inc operator. MongoDB expects a numerical value (integer, double, etc.).

## Bug Solution
The solution is to ensure that you always provide a numerical value to the $inc operator.
