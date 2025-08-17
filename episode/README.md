# Episode Query – GraphQL

This project demonstrates how to query a specific episode from the Rick and Morty GraphQL API.

## Endpoint
https://rickandmortyapi.com/graphql

## Query
We use the `episode(id: ID!)` field to fetch details of a specific episode.

### Fields Selected
- `id`
- `name`
- `air_date`
- `episode`

### Files
- `episode-id-1.graphql` → query for episode with id=1
- `episode-id-1-output.json` → result for episode with id=1
