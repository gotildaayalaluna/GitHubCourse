
# Copilot Evidence — Step 01

These are my notes for the code completion exercise.

## Prompt 1

"Complete this function to normalize usernames."
"Generate a robust slugify helper for lowercase ASCII and hyphens."

## Why you accepted/rejected the suggestion

I accepted the suggestions because they correctly implemented string manipulations such as lowercase conversions, string replacement, and regular expressions formatting as detailed in the docstrings. 

## Final check

The initial suggestion missed trimming trailing dashes or underscores, so I added the `.strip('_')` and `.strip('-')` respectively. 
