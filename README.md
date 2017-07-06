# Awesome Highoutput

## NodeJS Code Snippets
- [Idempotent Async Function](#idempotent-async-function)

### Idempotent Async Function
```js
class AwesomeClass {
  async awesomeFunc () {
    if (!this.awesomeFuncPromise) {
      this.awesomeFuncPromise = new Promise((resolve, reject) => {
        // insert code here
      })
    }

    return this.awesomeFuncPromise;
  }
}
```
