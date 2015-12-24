# Awesome Relay [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome resources for [Relay](https://github.com/facebook/relay), based on the [Awesome](https://github.com/sindresorhus/awesome/) project

# Table of Contents
- [Learning Resources](https://github.com/expede/awesome-relay#learning-resources)
  - [Documentation](https://github.com/expede/awesome-relay#documentation)
  - [Tutorials](https://github.com/expede/awesome-relay#tutorials)
  - [Overviews](https://github.com/expede/awesome-relay#overviews)
  - [FAQs](https://github.com/expede/awesome-relay#faqs)
  - [Videos](https://github.com/expede/awesome-relay#videos)
  - [Lists of Lists](https://github.com/expede/awesome-relay#lists-of-lists)
- [Libraries & Packages](https://github.com/expede/awesome-relay/blob/master/README.md#libraries--packages)
- [Tooling](https://github.com/expede/awesome-relay#tooling)
- [Miscellaneous](https://github.com/expede/awesome-relay#miscellaneous)
- [License](https://github.com/expede/awesome-relay#license)

# Learning Resources
## Documentation
- [Official Docs](https://facebook.github.io/relay/docs/getting-started.html#content) - Official Relay documentation.

## Tutorials
- [Getting Started with Relay](https://auth0.com/blog/2015/10/06/getting-started-with-relay/) - One of the few detailed walk throughs of hand-on Relay.
- [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6#.1i64q1pf9) - A complete workable example.

## Overviews
- [React Data Fetching with Relay](http://www.sitepoint.com/react-data-fetching-with-relay/) - Clear conceptual overview of Relay's moving parts and magic.

## FAQs
- [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47) - Common questions answered! Relay resources are scarce at the moment, so this is very helpful if you get stuck.

## Videos
- [Joseph Savona - Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg) - Conceptual overview of Relay from the Facebook team.

## Lists of Lists
- [Relay and GraphQL Introduction Materials](https://quip.com/oLxzA1gTsJsE)

# Libraries & Packages
- [`graphql-relay-js`](https://github.com/graphql/graphql-relay-js) - Simplifies creating a JS GraphQL server for `react-relay`.
- [Babel Relay Plugin](https://www.npmjs.com/package/babel-relay-plugin) - Use Relay the latest ES6+ syntax.
- [`react-router-relay`](https://github.com/relay-tools/react-router-relay) - `react-router` bindings for Relay. Greatly simplifies many local state UI uses cases.
  - [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9#.h91614i65) - A well-articulated walk through of `react-router-relay`, and the problems that it solves.
  - [`relay-nested-routes`](https://www.npmjs.com/package/relay-nested-routes) - Generate nested routes that reflect nested data. Helpful for managing deep data.
- [`relay-decorator`](https://github.com/4Catalyzer/relay-decorators) - Simply syntax for Relay containers with ES7 decorators (`@` syntax)
- [`recompose-relay`](https://www.npmjs.com/package/recompose-relay) - Ease composition of Relay containers by currying and providing the component after the container.
- [`relay-local-schema`](https://github.com/relay-tools/relay-local-schema) - Use a local schema; no need for a remote GraphQL server.
- [`react-native-relay`](https://github.com/lenaten/react-native-relay) - Use Relay with React Native.

# Tooling
- [GraphiQL](https://github.com/graphql/graphiql) - A library to introspect GraphQL, test queries and mutations.
  - [GraphiQL App](https://github.com/skevy/graphiql-app) - A standalone app for viewing GraphQL, introspection docs, and testing queries/mutations. Invaluable for debugging your Relay app.

# Miscellaneous
- [Relay Starter Kit](https://github.com/relayjs/relay-starter-kit) - An app that it already set up with a basic setup. Just clone and tweak to suit your needs!
- [Simple Relay Starter](https://github.com/mhart/simple-relay-starter) - A Browserify version of the [Relay Starter Kit](https://github.com/relayjs/relay-starter-kit).
