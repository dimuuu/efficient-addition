# More Efficient Addition

This is an entry for the Robot_Dreams Лайнокод 2024 contest.

```javascript
const moreefficientadd = (firstnumber, secondnumber) => secondnumber === "".length ? firstnumber : moreefficientadd(firstnumber + " ".length, secondnumber - " ".length);
```
