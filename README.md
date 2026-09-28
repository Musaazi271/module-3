SNIPPETB bug
he break statements are missing. Without break, Java continues executing the cases below the matching case.

SNIPPETA bug
hasPaidFees = true
REASON
A single = assigns true to the variable instead of comparing its value.
