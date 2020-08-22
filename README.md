# Walmart Partner APIs PHP SDK
This library provides an easy to use interface to [Walmart's Partner APIs](https://developer.walmartapis.com/).

## Installation
It is easiest to use Composer "https://getcomposer.org/" to install, simply run:

composer require  Sed9yDataBank/Client-Walmart-Lib :^1.0.9

## Usage Documentation
 See [docs/README.md](docs/README.md)

## API Coverage
Currently 100% (19 of 19) are supported by this SDK

| Object    | Operation                     | SDK Class -> Method   | Unit / Int Tested   | API Docs |
|-----------|-------------------------------|-----------------------|---------------------|----------|
| Feeds     | Get all feed statuses         | Feed -> List          | Yes / Yes           |https://developer.walmartapis.com/#get-all-feed-statuses |
|           | Get a feedItems status        | Feed -> GetFeedItem   | Yes / Yes           |https://developer.walmartapis.com/#get-a-feeditems-status |
|           | Get a feed status             | Feed -> Get           | Yes / Yes           |https://developer.walmartapis.com/#get-a-feed-status |
| Items     | Get all items                 | Item -> List          | Yes / Yes           |https://developer.walmartapis.com/#get-all-items |
|           | Get an item                   | Item -> Get           | Yes / Yes           |https://developer.walmartapis.com/#get-an-item |
|           | Retire an item                | Item -> Retire        | Yes / Yes           |https://developer.walmartapis.com/#retire-an-item |
|           | Bulk create/update items      | Item -> Bulk          | Yes / Yes           |https://developer.walmartapis.com/#bulk-createupdate-items |
| Prices    | Update a price                | Price -> Update       | Yes / Yes           |https://developer.walmartapis.com/#update-a-price---v3-endpoint |
|           | Update bulk prices            | Price -> Bulk         | Yes / Yes           |https://developer.walmartapis.com/#update-bulk-prices |
| Orders    | Get all released orders       | Order -> ListReleased | Yes / Yes           |https://developer.walmartapis.com/#get-all-released-orders |
|           | Get all orders                | Order -> List         | Yes / Yes           |https://developer.walmartapis.com/#get-all-orders |
|           | Get an order                  | Order -> Get          | Yes / Yes           |https://developer.walmartapis.com/#get-an-order |
|           | Acknowledge purchase order    | Order -> Acknowledge  | Yes /               |https://developer.walmartapis.com/#acknowledging-purchase-orders |
|           | Cancel order lines            | Order -> Cancel       | Yes /               |https://developer.walmartapis.com/#cancelling-order-lines |
|           | Refund order lines            | Order -> Refund       | Yes /               |https://developer.walmartapis.com/#refunding-order-lines |
|           | Shipping notification/updates | Order -> Ship         | Yes /               |https://developer.walmartapis.com/#shipping-notificationsupdates |
| Inventory | Get inventory for an item     | Inventory -> Get      | Yes / Yes           |https://developer.walmartapis.com/#get-inventory-for-an-item |
|           | Update inventory for an item  | Inventory -> Update   | Yes / Yes           |https://developer.walmartapis.com/#update-inventory-for-an-item |
|           | Bulk update inventory         | Inventory-> Bulk      | Yes / Yes           |https://developer.walmartapis.com/#bulk-update-inventory |


