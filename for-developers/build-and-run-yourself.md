# Build and Run Yourself

## Prerequisites

* [x] &#x20;Install the [IC SDK](https://internetcomputer.org/docs/current/developer-docs/getting-started/install). For local testing, `dfx >= 0.22.0` is required.
* [x] &#x20;Install the  [Mops (Motoko Package Manager) ](https://mops.one/docs/install)

## Start the local replica

Open a new terminal window _in the project directory_, and run the following command to start the local replica. The replica will not start unless [dfx.json](https://github.com/dfinity/oisy-wallet/blob/main/dfx.json) exists in the current directory.

```
dfx start --background
```

When you're done with development, or you're switching to a different dfx project, running

```
dfx stop
```

from the project directory will stop the local replica.

## Run Fradium Locally

Make sure you switch back to the project root directory.

First, install the frontend dependencies by running

```
npm ci
```

To build and deploy the project locally, first create a `.env.development` file by copying the [.env.example](https://github.com/dfinity/oisy-wallet/blob/main/.env.example) file. Once you've correctly set the api keys for all the different services that OISY needs, then run:
