# Incorrect Usage of $inc Operator in MongoDB Update Operation
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation. Using a string instead of a number with the `$inc` operator will not increment the field as expected. The field will instead be set to the string value.