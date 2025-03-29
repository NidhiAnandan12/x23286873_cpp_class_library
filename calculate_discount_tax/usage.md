# Usage

To use the `calculate_discount_tax` package, you can utilize its various calculations functions such as `calculateTax`, `calculateDiscount`. Below is a quick example demonstrating how to use these functions.

## Example Code

```python
from calculate_discount_tax import calculateTax,calculateDiscount
print("Tax Amount:", calculateTax(amount,tax_rate)) #100,5.0 - returns 105
print("Discount Amount ", calculateDiscount(amount,discount_rate)) #100,10 - returns 90 