# SECRET KEY
## example
Alert when user type "wasans"
```js
SecretKey.add('wasans', () => {
    alert('와! 샌즈 아시는구나!');
});
```

Remove added secretkey event
```js
SecretKey.remove('wasans');
```