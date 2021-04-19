# Forumsite-demo

## Intro/Info

Hey there! I'm trying out this GraphQL and Typescript FULL STACK TUTORIAL from Ben Awad.

#### Fullstack React GraphQL TypeScript Tutorial: https://www.youtube.com/watch?v=I6ypD7qv3Z8&list=PLalFRuGGwxXdyB28tvl169EkTTw30PXIe&index=2

My goal here is to learn more about using GraphQL and Typescript with React.

## Initial Project Set Up

#### Setting Up TypeScript & Node

- added `-D @types/node typescript`
  - Allows us to use all the built in Node Functions
- ran `npm init -y`
- added `ts-node`
  - _Ben added this then stated he doesn't use it because it's slow and it doesn't reflect production_
- added `npx tsconfig.json`
  - _Ben created this config file_
- ran `yarn watch`
  - watches for changes & compiles js files
- added `nodemon`

#### Setting Up Our DB Needs

- Added Mikrp Orm `yarn add @mikro-orm/cli @mikro-orm/core @mikro-orm/migrations @mikro-orm/postgresql pg`
