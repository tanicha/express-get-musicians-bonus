![logo](https://user-images.githubusercontent.com/44912347/202296600-c5f247d6-9616-49db-88f0-38433429d781.jpg)

# Express Get Musicians Bonus
**TASK**: In this assignment, you’re are given two models Band and Musician. The following associations exist with these two models:

```js
Musician.belongsTo(Band, {foreignKey: 'band_id'})
Band.hasMany(Musician, {foreignKey: 'band_id'})
```

This means that a Band may contain one or more musicians in them. The goal of this assignment is to be able to make a GET request to:
- Get a list of all the bands in the Band database, including the musician(s) that are in that band. 
- Get a particular band from the Band database, including the musician(s) in that particular band. 

## Instructions
- Create a `GET` request to the endpoint “bands” and return all the bands in the Bands Model including the musicians that are part of that band
- Create a `GET` request for the endpoint “bands” with a Route Parameter. Return the band based on the ID passed into the request, and include the musician(s) that are part of that particular band.
