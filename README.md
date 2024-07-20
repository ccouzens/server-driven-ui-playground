# Server Driven UI Playground

A grocery shop website built using Server Driven UI designed to try out ideas.

The first version of this project will provide:

- A grocery data collection as JSON
- A page data collection as JSON
- A nodejs server which recieves requests for page data, creates it from the 2
  data collections and responds with JSON. For lack of a better term this will
  be referred to as the backend server.
- A nodejs webserver which requests page data from the backend server and
  creates an HTML page from it.

## The goal

The goal of this project is to build a learning playground where the different
building blocks can be substituted out so that someone can focus their learning
on a small part of the whole. Some ideas:

- Replace the data collections with a database or content-management-system.
- Replace the nodejs backend server with a Rust, go, Python or Kotlin server.
- Change the protocol between the frontend and the backend to be GraphQL.
- Write frontends using Android, iOS or Windows technology or Flutter.
- Write web frontends using SSG (Server Side Generated pages), SSR (Server Side
  Rendered pages) or SPA (Single Page Application - Client Side Rendered).
- Write web frontends using whichever Javascript framework you'd like to learn.
- Create mockups for new pages or to redesign existing pages.
- Implement different page designs or different design systems.
