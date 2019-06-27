# Fork of [Lucas Bento](https://github.com/lucasbento)'s [GraphQL Pokémon](https://github.com/lucasbento/graphql-pokemon/)
### Changes
* New query to get a range of Pokémon: 
```
pokemonsRange(start: Int!end: Int!): [Pokemon]
```
* Included `babel-polyfill` to dependencies for Heroku