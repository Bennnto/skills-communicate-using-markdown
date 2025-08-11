```
git config user.name Bennnto
git config user.email ben.promkaew@icloud.com
```

```Javascript
async function searchStoreProduct(product_name) {
  const api = `https://mdn.github.io/learning-area/javascript/apis/fetching-data/can-store/products.json`
  const resp = await response
  if(!resp.ok) {
   throw new Error (`response status: ${response.status}`);
  const data = await resp.json()
  if(!Array.isArray(data) || data.length === 0) {
  return null
  }
  const itemname = String(product_name).toLowerCase();
  const match => data.find(item => {typeof item.name === itemname});
   return match.price
 }
}
```

```Python
let a = 2
print(a)
```

