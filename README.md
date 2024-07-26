# Redwood Tutorial App

This repo is the final version of a blog site created with RedwoodJS.


## Setup

The [tutorial itself](https://redwoodjs.com/docs/tutorial/chapter1/prerequisites) contains instructions for getting this repo up and running, but here is a summary of the commands:

```bash
git clone https://github.com/redwoodjs/redwood-tutorial
cd redwood-tutorial
yarn install
yarn rw prisma migrate dev
yarn rw prisma db seed
yarn rw dev
```


to start the rw dev server and GraphQL:
yarn rw dev
http://localhost:8910/
http://localhost:8911/graphql

to start Prisma Studio:
yarn rw prisma studio
http://localhost:5555/

to start Storybook:
yarn rw storybook
http://localhost:7910


