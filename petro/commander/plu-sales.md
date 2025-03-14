# PLU Sales

## Overview

PLU means “Price Look Up” and a PLU sale is one whose price is defined and can be “looked up” on the system’s price book using a numeric identifier. There are a number of ways to enter a PLU number (scanner, menu or button assignment or manually keyed).

When this number (which may also be a barcode) is provided to the system, the system can locate the item’s price, taxability, reporting department and other details associated with that number. So, all that is required to sell a PLU item is to provide the identifying number along with the quantity of the item being sold.

Our system supports the concept of “modifiers” to provide a mechanism to more specifically define the product when the same barcode is used to indicate different packaging of the same product. This is seen most often on canned soda (singles, 6-packs, etc). The combination of the PLU# and modifier uniquely identifies a product along with its price, taxability and other information. For most PLUs, this modifier value is zero.

## Modifiers

A PLU is made up of a PLU number and a modifier number. A single PLU can have up to 255 modified versions. Modifiers let you group similar items into the same PLU number.

For example, you might want to group all Coke products:
