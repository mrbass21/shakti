# Authentication

## Description
The authentication required for the Shakti API endpoint generally consists of two token values: NetflixId and SecureNetflixId. These are both passed in as cookie values for requests with every endpoint, unless otherwise stated.

Obviously, this means that in order to hit the API endpoints, you must be subscribed to Netflix!

All tokens are tied to a specific user, and are further unique on a per-profile basis, not just account.

For example: When you switch profiles on the same account, both the NetflixId and SecureNetflixId will both change.

We will not go any further in describing how to get authenticatation tokens other than to say we heavily discourage you from taking Netflix user credenials directly (I.E. Username and Password).