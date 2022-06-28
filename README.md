# Learning-React-Part-4
Small project to learn the non modern Class based components as some existing project I might work on in the future might use those!

## Setup..

After cloning the repository and directing yourself to it all you need to do is!

```sh
npm install
```

```sh
npm run start
```

Additionally you will need to create a firebase project and in said project you need to create your dummy database

```sh
https://firebase.google.com/
```

After creating the project you can create a table and call it whatever you want, create the records in the form that Firebase accepts 

```sh
> m1
  -> name: '...'
  -> description: '...'
  -> price: '...'
> m2
  -> name: '...'
  -> description: '...'
  -> price: '...'
```

and replace your custom Firebase URL on line 32 in Cart.js

```sh
    await fetch('YOUR-FIREBASE-LINK/orders.json', {
```

and on line 15 in AvailableMeals.js

```sh
        'YOUR-FIREBASE-LINK/meals.json'
```
