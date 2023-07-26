## Getting started

First, install the dependencies using `npm install` or `yarn install`.

Second, run the setup commends:

```bash
yarn db:dev:up
yarn prisma:dev:deploy
# OR
npm run db:dev:up
npm run prisma:dev:deploy
```

To remove docker env use `yarn db:dev:rm`or `npm run db:dev:rm`

Then, run the development server:

```bash
yarn start
# OR
npm run start
```

Then, open [http://localhost:3000](http://localhost:3000) with your browser to see the result (if it doesn't open automatically).

To other commend lock to package.json and you can use them by yarn or npm
