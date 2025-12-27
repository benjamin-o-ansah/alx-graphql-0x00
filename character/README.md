# alx-graphql-0x00

# Rick and Morty GraphQL Character Fetcher

This project fetches details for specific characters from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

## Query Structure
The query uses the `character(id: ID!)` field to retrieve:
- **id**: Unique identifier
- **name**: Full name of the character
- **status**: 'Alive', 'Dead', or 'unknown'
- **species**: Biological species
- **type**: Subspecies or specific type description
- **gender**: 'Female', 'Male', 'Genderless', or 'unknown'

## Characters Fetched
1. Rick Sanchez (ID: 1)
2. Morty Smith (ID: 2)
3. Summer Smith (ID: 3)
4. Beth Smith (ID: 4)
