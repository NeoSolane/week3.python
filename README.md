# week3.python
def "calculate_discount"(price,discount_percentage:)
calculate the final priceafter applying a discount if it is 20% or higher
:param price :Original price of the item(float)
:param discount_perecent:Discount percentage(float)
:return :final price after dicountbor original price if discount is less than 20%
if discount_percent>=20%
discount_amount=price * (discount_percent/100)
return price-discount-discount_amount
return price
try:
original_price=float(input("Enter the original price of the item"))
discount_percentage=float(input("Enter the discount percentage:"))
final_price=calculate_discount(original_price,discount_percentage)
print(f"finale price:${finale_price:.2f}")
Except ValueError:
print("please enter valid numeric values for price and discount percentage")
