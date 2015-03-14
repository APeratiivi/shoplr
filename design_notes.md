# shoplr design notes

Responsive web application for creating and sharing shopping lists as easily as possible.

## key principles

1. intuitive to create and share shopping lists
2. collections of shopping lists for sharing with regular users
3. no login
4. powerful search tool for finding already add products
5. sort tool that let's users create sorts based on 

## features

1. create shopping list
2. sharing of shopping list through simple url
3. add shopping list to collection
4. sharing of shopping list collections through simple url
5. suggestive input for products in search
6. adding of product: name, amount and category

## technologies

1. full clojure stack with reagent/om
2. bootstrap: front
3. elastic: search
4. postgres: db
5. git and github: version control
6. project management: kanbanize (for now)

## things to find out

1. sorts: how to save them, are they shared or user specific?
2. reactive programming: how to refresh front when another user updates open shopping list?
3. how to prevent trolls getting access to shopping list collections/shopping lists?
4. categories: preset or preset + user additions?
