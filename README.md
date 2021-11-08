# json-server-demo

In the project directory, you can run:

### `npm run serve-json`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Use the browser address bar to test the different scenarios...

| Description | Url |
| ---- | ---- |
|To return a list of all products | [http://localhost:3000/products](http://localhost:3000/products) |
|To return a single product (id=1) | [http://localhost:3000/products/1](http://localhost:3000/products/1) |
|To filter a list of products by the category 'electronics' | [http://localhost:3000/products?category=electronics](http://localhost:3000/products?category=electronics) |
|To filter a list of products by the category 'electronics' and the 'type' key inside the nested 'discount' object| [http://localhost:3000/products?category=electronics&discount.type=shipping](http://localhost:3000/products?category=electronics&discount.type=shipping) |
|To return a list of all products sorted by 'price' on ascending order | [http://localhost:3000/products?_sort=price](http://localhost:3000/products?_sort=price) |
|To return a list of all products sorted by 'price' in descending order | [http://localhost:3000/products?_sort=price&_order=desc](http://localhost:3000/products?_sort=price&_order=desc) |
|To return a list of all products sorted by 'price' in descending order, and 'category' in ascending order | [http://localhost:3000/products?_sort=price,category&_order=desc,asc](http://localhost:3000/products?_sort=price,category&_order=desc,asc) |

