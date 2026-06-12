# Document your edge case here

## Edge case identified
If there are no students in the database, the stats might be undefined and might
crash the endpoint

## How this was accounted for in implementation
I check if the list is empty after the marks are collected and return a separate result if the marks array is empty. This ensures the math functions don't die. 
