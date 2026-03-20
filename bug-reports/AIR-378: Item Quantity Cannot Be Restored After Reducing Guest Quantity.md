# Bug Report – Item Quantity Cannot Be Restored After Reducing Guest Quantity

## Environment
Staging  
https://staging.airtopiapark.com  

## Summary
When the guest quantity is reduced and then increased back to the original value, the system does not allow adding the required number of **Grip Socks** items again. The **"+" button remains disabled**, even though the quantity of guests has increased.

## Steps to Reproduce

1. Select a bundle product with **Quantity = 20 guests**.
2. Add **Grip Socks – General** or **Grip Socks – Party** for all guests.
3. Reduce the **guest quantity**.
4. Increase the **guest quantity back to 20**.

## Actual Result
The **"+" button remains disabled**, preventing the user from adding items to match the guest quantity.

## Expected Result
The system should allow increasing item quantity again when the guest quantity is increased.

## Impact
The order cannot be completed because item quantities cannot be adjusted correctly.

## Notes
The original UI issue for bundles with more than 10 items appears to be fixed, but a new quantity synchronization issue was discovered during testing.

# Screenshots

![Guest Quantity - failure quantity](../screenshots/AIR-378-1.png)

![Guest Quantity - failure quantity](../screenshots/AIR-378-1.png)
