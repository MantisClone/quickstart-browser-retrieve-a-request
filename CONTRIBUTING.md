This CodeSandBox shows how to use the Request Client library to retrieve a user's requests.

## Description

This CodeSandBox performs the following actions:

1. Import the `@requestnetwork/request-client.js` library. 
2. Construct a `RequestNetwork` object connected to the Goerli Gateway.
3. Call `fromIdentity()`, passing in a user's address.
4. Call`getData()` on the returned requests 
5. Display the data in a simple table.
6. Display the raw request JSON.

## Getting Started

Start by viewing the `app/page.tsx` file. 

## Troubleshooting

If the dev:3000 tab displays a 504 Gateway Timeout error, try restarting the dev:logs tab. If that doesn't work, try restarting the whole sandbox.


## Learn More

To learn more about Request Network, take a look at the following resources:

- [Request Network Documentation](https://docs.request.network) - learn about Request Network features and API
- [Request Network Github repository](https://github.com/RequestNetwork/requestNetwork) - your feedback and contributions are welcome!
