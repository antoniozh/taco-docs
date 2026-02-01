# Common issues

Under this page, some common issues will be listed. Some are fixable by the user and some are just requirements that are so specific that they are not listed in the main page as they are fulfilled by a vanilla setup

## Cannot log in to TastyIgniter server

- Is the login username correct? (For v3, enter username, for v4, enter email address)
- Is the API extension installed and updated to the newest version?
- Does the logged-in user have the correct permissions and locations assigned to list and retrieve the orders?

## Pending orders not loading

Make sure the order status ID does not exceed 4 for all orders in progress. This is a hardcoded status ID and there is currently no API information about which order status are considered "final".

## No notifications received

This could have multiple reasons, here's a list of common mistakes users can check:

- Are notifications enabled for the app?
- Is silent mode activated?
- Is the webhook correctly configured? Is it checked on order events, does it contain the restaurant's correct and same URL that the smartphone uses to log in?
- Do the logs for the Webhook show successful POST requests?
