# hybridapps
JavaScript library for hybridapps.net
# main
```js
async function main(){
    const {hybridapps} = require('./hybridapps');
    const url= new hybridapps();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
