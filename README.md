# Australia Post Tracking API & Webhooks

Use Track123 to track Australia Post shipments through one unified shipment tracking API.

Track123 lets your application register Australia Post tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- Australia Post carrier code: `australia-post`

- [Track Australia Post packages on Track123](https://www.track123.com/carriers/australia-post)

- [Australia Post API integration page](https://www.track123.com/carriers/australia-post/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track Australia Post shipments with Track123. It is not official Australia Post API documentation.

## Australia Post tracking API integration

When your application already knows that a shipment is handled by Australia Post, set `courierCode` to `australia-post` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [Australia Post tracking webhook](webhook.md)
- [Australia Post tracking statuses](tracking-status.md)
- [Australia Post API errors and rate limits](errors-and-rate-limits.md)

## Australia Post tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track Australia Post packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [Australia Post tracking on Track123](https://www.track123.com/carriers/australia-post).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by Australia Post unless explicitly stated.
