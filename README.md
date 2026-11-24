# Full Stack Open — Part 11

Live app: https://fullstack-open-part11.onrender.com/

Solutions for [Full Stack Open, part 11: CI/CD](https://fullstackopen.com/en/part11).

Parts 0–5: [fullstack-open-part00-05](https://github.com/Kopfdreher/fullstack-open-part00-05).

A React Pokedex that loads the first 50 Pokémon from [PokéAPI](https://pokeapi.co/). Jest and Testing Library cover the list and detail views. ESLint, a production Webpack build, and Express serve the pipeline the course deploys.

| Directory | What it covers |
| --- | --- |
| `.` | Pokedex UI, Jest tests, ESLint, and the production server |

From this directory:

- `npm install`
- `npm start` — Webpack dev server on port 8080
- `npm test` — Jest
- `npm run eslint`
- `npm run build` — production bundle
- `npm run start-prod` — Express serving that bundle
