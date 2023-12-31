## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## API Reference

```
  - BASE_URL: https://<DOMAIN>/v1/api/

  [Auth]
  - POST /auth/signin
  - POST /auth/register

  [Users]
  { Protected }
  - GET /users/profile
  - GET /users
  - GET /users/:id
  - PATCH /users/:id
  - DELETE /users/:id

  [Wallet]
  { Protected }
  - GET /wallet
  - GET /wallet/transactions
  - GET /wallet/recharge

  [Games]
  - GET /games
  - GET /games/current
  {Protected}
  - GET /games/:id
  - GET /games/:id/wins
  - GET /games/wins
  - PATCH /games/:id
  - DELETE /games/:id

  [Bets]
  { Protected }
  - POST /bets
  - GET /bets [if user only return bets of themselves else for admin return all]
  - GET /bets/:id

  [Analytics]
  { Protected :: ADMIN_ONLY }
  - GET /analytics/activity
  - GET /analytics/users
  - GET /analytics/earnings
```
