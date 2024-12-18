# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field in a document.  However, passing a string value instead of a number will result in an error or unexpected behavior.

## Bug
The bug lies in the incorrect usage of the `$inc` operator, where a string ("1") is used instead of a number (1). This causes MongoDB to either throw an error or unexpectedly modify the document.

## Solution
The solution involves using a numerical value (1) instead of a string ("1") when incrementing the field using the `$inc` operator.