# Excel-Assignment-2--Data-Cleaning-and-Transformation

## Overview
A workflow auditing, cleaning, and transforming an unstandardized retail dataset in Excel.

## Key Actions Taken
* **Missing Values**: Imputed prices via mean ($309.30); filled missing categories labeled as "Not Available".
* **Text Cleaning**: Standardized product casing using `=PROPER()` and corrected the category typo `Electroni` $\rightarrow$ `Electronics` via Find & Replace.
* **Deduplication**: Removed 3 duplicate rows (HP Laptop, Bose Headphones, Samsonite Bag), reducing data from 34 to 31 records.
* **Split & Merge**: Split `Product ID` into date and country code; merged brand and name into `Product Brand` (`=D2&" "&C2`).
* **Formatting**: Applied Currency (`$`) to `Price` and custom date format `DD-MM-YYYY` to `Manufacturing Date.
* **Conditional Formatting**: Added Price data bars and highlighted entire rows for `Electronics` using `=$H2="Electronics"` across range `A2:J32`.
