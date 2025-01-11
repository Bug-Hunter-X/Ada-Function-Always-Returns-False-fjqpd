# Ada Function Bug

This repository demonstrates a common error in Ada programming: a function that doesn't produce the expected output due to a flawed conditional statement.  The `Check_Range` function is intended to determine whether an input integer is greater than 10. However, due to a logical error, it consistently returns `False`. The `Main` procedure showcases how this incorrect behavior manifests in a larger program.

The solution branch contains a corrected version of the function with the logical error fixed.