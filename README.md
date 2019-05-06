# Katapi

> A kata to practice your API design and development skills.

This [kata](https://en.wikipedia.org/wiki/Kata_(programming)) offers a set of features to practice your API programming skills. It covers basic HTTP verbs and codes.

## Features

Shopping API with products, orders and bills.

* Products
  * Can be listed, created, updated, found by id, deleted
  * Have an `id`, `name`, `price` and `weight`
  * Products can be sorted by `name`, `price` or `weight`
* Orders
  * Can be created, listed, updated and deleted
  * Have a status, a product list with a quantity per product, a shipment amount, a total amount and a weight
  * Orders status can be `pending`, `paid` or `canceled`
  * Are offered 5% discount when the price exceeds 1000€
  * Shipment costs 25€ for every 10 more kg (50€ for 20kg, 75€ for 30kg, etc.)
* Bills
  * Can be listed
  * Have an `amount` and a `creation date`
  * Are automatically generated when an order status is set to `paid`
