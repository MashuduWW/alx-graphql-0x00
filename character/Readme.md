# **GraphQL Character Fetch: Rick and Morty Endpoint**

This README provides a GraphQL query to fetch details for specific characters from the Rick and Morty API using the character(id: ID!) field.

**Endpoint**

The GraphQL endpoint for this API is: <https://rickandmortyapi.com/graphql>

**GraphQL Query**

This query fetches the id, name, status, species, type, and gender for characters with IDs 1, 2, 3, and 4.

query GetMultipleCharacters {

character1: character(id: 1) {

- id

- name

- status

- species

- type

- gender

}

character2: character(id: 2) {

- id

- name

- status

- species

- type

- gender

}...



**How to Use This Query**

1. **Open a GraphQL Client:** You can use a tool like GraphQL Playground, Insomnia, Postman, or a web-based GraphQL explorer (like the one provided by the Rick and Morty API directly at the endpoint URL).
2. **Set the Endpoint:** Configure your client to use <https://rickandmortyapi.com/graphql> as the GraphQL endpoint.
3. **Paste the Query:** Copy and paste the "GraphQL Query" provided above into your client's query editor.
4. **Execute the Query:** Run the query.

**Expected Output (Example)**

When you run the query, you will receive a JSON response similar to this (truncated for brevity):

{

"data": {

- "character1": {

- "id": "1",

- "name": "Rick Sanchez",

- "status": "Alive",

- "species": "Human",

- "type": "",

- "gender": "Male"

},

"character2": {

- "id": "2",

- "name": "Morty Smith",

- "status": "Alive",

- "species": "Human",

- "type": "",

- "gender": "Male"

}...

Author: Mashudu Molema

