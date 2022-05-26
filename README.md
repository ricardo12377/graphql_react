yarn add @apollo/client graphql

1 - provider in index.js.

2 - in context import  gql e  use query


3- query para encontrar um valor

query ($title: String) {
    collection(tittle: $tittle) {
        
    }
}
