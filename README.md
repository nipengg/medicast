## Instalation

### Specification
- NPM
- Getstream account

### How to install

1. Clone or download source code
    - In terminal, clone repo `git clone https://github.com/nipengg/medicast.git`
2. `cd medicast`
3. Install node module using `npm install` for both client and server side
4. `cp .env.example .env`
    - If not using git, manually change `.env.example` to `.env`
5. Change **API_KEY, API_SECRET, APP_ID** from your getstream project on `.env`
6. `cd client` and then run `npm start`
7. Open another terminal then `cd server` and then run `npm run dev` or `nodemon` for development
8. Done