# fake-orders-package
## create your fake orders


## Installation

    npm i fake-orders-package


## Usage

For use the fake orders

```js
var fakeorders = require('fake-orders-package');

console.log('orders', fakeorders.all()); // outputs all
console.log('orders', fakeorders.add(
  {product: "Coca", price: "3"})); // add your order
console.log('orders', fakeorders.update(2,
    {status: "closed"})); // close your order
fakeorders.reset(); // reset fake orders;
fakeorders.delete(1); // delete order with id 1
fakeorders.getById(1); // return order with id 1

```
