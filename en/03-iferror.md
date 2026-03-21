## Step 3. Error handling for products not found in the Price list: fill the Price column with "out of stock".

**If the product is missing**, the cell displays "#N/A". To replace "#N/A" with "out of stock", add the IFERROR function to the formula:

```excel
=IFERROR( VLOOKUP formula + IF condition ; "out of stock" )
```

*IFERROR*

```excel
=IFERROR( VLOOKUP( A2 ; 'Price list'!A:C ; IF( B2="Retail" ; 2 ; 3 ) ; FALSE ) ; "out of stock" )
```
*IFERROR + VLOOKUP + IF condition*
