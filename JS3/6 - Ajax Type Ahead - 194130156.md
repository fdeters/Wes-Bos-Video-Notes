# Ajax Type Ahead

* Instead of defining a new function to format place.population with commas, try the built-in Number.prototype.toLocaleString() function -> Number(place.population).toLocaleString() <- This will make sure that the number is formatted correctly for the user's locale (e.g. spaces instead of commas for most of Europe).
