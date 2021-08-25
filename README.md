# Bopify (SvelteJS)

Spotify But Bop-ier

## Requirements

You will need your own:

- Client ID
- Client Secret
- Active Spotify Subscription

## Set Up

1. Clone the root project with `git clone https://github.com/victornguyen75/bopify-svelte.git` in the terminal
2. Pull all submodules recursively with `npm run pull` or `yarn pull` in the terminal
3. Update all submodules recursively with `npm run update` or `yarn update` in the terminal

## Install Dependencies

1. Install the dependencies for each submodule with `npm run install` or `yarn install` in the terminal
2. Obtain the Spotify Client ID and Client Secret from https://developer.spotify.com/
3. Add the following environment variables for both the client and server modules.

### Client

Your `CLIENT_ID` should be the client ID from the developer.spotify.com

### Server

Your `/server.env` file should contain:

```
REDIRECT_URI=http://localhost:5000
CLIENT_ID=your_own_client_id_from_the_spotify_API_and_docs
CLIENT_SECRET=your_own_client_secret_from_the_spotify_API_and_docs
```

## Run the Application

1. In one terminal, navigate to `/client`
2. Run `npm start` or `yarn start` in the terminal
3. In a separate terminal, navigate to `/server`
4. Run `npm start` or `yarn start` in the terminal
5. Open a new tab on your browser for `localhost:5000`
6. If you wish to debug the `/client`, run `npm run dev` or `yarn dev` in the terminal
7. If you wish to debug the `/server`, run `npm run dev` or `yarn dev` in the terminal

## ReactJS vs SvelteJS?

Follow the [discussion](https://github.com/victornguyen75/bopify-svelte/discussions/1) to see how two different Spotify Clone Applications compare between ReactJS and SvelteJS.
