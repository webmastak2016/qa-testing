# Test Cases – Guest Membership Validation

## AIR-362 (Test Guest creation without missing contact information)

## TC-001 – Phone Number Validation

### Preconditions

User opens the Guest Explore Memberships page.

URL:
https://staging.airtopiaparks.com/guest/explore/memberships

### Steps

1. Open the Guest Explore Memberships page.
2. Start the membership signup flow.
3. Enter an invalid phone number (letters or symbols).
4. Click Continue.

### Expected Result

The system should display a validation error and prevent the user from continuing.

### Actual Result

The system allows the user to continue with an invalid phone number.

### Status

Failed

### Attachments

Step 3 – Invalid phone number entered

![Invalid phone input](../screenshots/phone-validation-guest-membership-step3.png)

Step 4 – System allows proceeding with invalid phone number

![Form proceeds with invalid phone](../screenshots/phone-validation-guest-membership-step4.png)
