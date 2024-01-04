# this is my first commit to the md
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```
getProducts(){
    const dbInstance = collection(this.firestore, 'products');
    getDocs(dbInstance) 
    .then((response) => {
      this.products = [...response.docs.map((products) => {
        return { ...products.data(), id: products.id}
      })]
    })
  }
  ```
- [x] Turn on GitHub Pages
- [x] Outline my portfolio
- [ ] Introduce myself to the world
