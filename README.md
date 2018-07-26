This is a Hacker News Clone React+Apollo  Project based from the tutorial of [REACT+Apollo](https://www.howtographql.com/react-apollo/0-introduction/)

Server code came from [GraphQL+NodeJS](https://github.com/howtographql/graphql-js)

1. clone project
2. cd into project
3. `yarn install`
4. cd into project/server dir
5. `yarn install`

- to start server while in server dir:
`yarn start`

- to start server with graphQL playground in client while in server dir:
`yarn dev`

- to start client side while in project dir:
`yarn start`

Make sure that you deployed your prisma ahead of this by `yarn prisma deploy` or `prisma deploy` if you have global prisms-cli

6. copy the HTTP value and paste it on __PRISMA_ENDPOINT__ placeholder in `server/src/index.js` in key `endpoint`

If you forgot the values of your deployed prisma just type in terminal `yarn prisma info`
