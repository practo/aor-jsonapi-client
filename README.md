# JSON API REST client for Admin-on-rest.
This is custom implementation of JSON API REST client forked from (https://github.com/moonlight-labs/aor-jsonapi-client).

## Installation

The library can be installed using:

```sh
npm install git+https://github.com/practo/aor-jsonapi-client.git
```
It can also be installed using yarn:
```sh
yarn add git+https://github.com/practo/aor-jsonapi-client.git
```

## Usage

```js
//in app.js
import React from 'react';
import { Admin, Resource } from 'admin-on-rest';
import jsonAPIRestClient from 'aor-jsonapi-client/build/restClient';

const restClient = jsonAPIRestClient('http://localhost:3000');

const App = () => (
    <Admin dashboard={Dashboard} restClient={restClient}>
        ...
    </Admin>
);

export default App;
```
