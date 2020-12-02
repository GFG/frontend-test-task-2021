# Whisky test task

One little known whisky exchange company created an internet store, 
so the clients could order their favourite drink online.

It worked really well, and agents who sold whisky on the platform used an integration tool 
to provide order data. This tool used a GraphQL API to communicate with a backend.

At some point agents requested a web frontend to show the data, as well as create orders.

## Requirements

* A frontend application should be created in pods/frontend folder
* It should connect to the GraphQL API, where user should be able to authorise
  * auth might be fake (just select current user) or real (in that case backend should be changed)
* List of current orders must be shown
* A form to create new order must be created
  * List of products must be shown
  * User must be able to add/remove items to the order
  * Before creating the order, user must be able to preview the order and enable discount
  * Order must be created in the system and be available on order list page

## Expectations

* A code must be working and readable. We believe that code is not only written for machines to read, but also for people
* Tests would be nice. Code might look well, but it's also nice to see the green page with "All tests pass" text on it
* We use React and TypeScript. It is not required to write the solution using them, but it is strongly recommended to do so
* Page is not expected to have completely innovative design, but it would be nice to have something that is somewhat
nice to look at. It is advised to use some UI libraries like Material UI or such to minimise time on writing styles
