# Lighthouse runner

## Command

1. `npm install`
2. run below:

`node lh --target [site] --device [mobile | desktop | all] --count [num]`

ex:
`node lh --target https://google.com --device all --count 5`
`node lh --target https://google.com --device mobile --count 5`
`node lh --target https://google.com --device desktop --count 5`
