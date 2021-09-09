# Start Front-End
```bash
# react app
npx create-react-app myApp

# install bootstrap and router
npm i bootstrap reactstrap react-router-dom

# add bootstrap
import 'bootstrap/dist/css/bootstrap.min.css';
import { Button } from 'reactstrap';

# install font-awesome
npm i @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/react-fontawesome

# add font-awesome
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faCoffee } from '@fortawesome/free-solid-svg-icons'
const element = <FontAwesomeIcon icon={faCoffee} />

```


```bash

# Firebase Configure
npm i firebase

import firebase from "firebase";

// Initialize Firebase
if (!firebase.apps.length) {
  firebase.initializeApp(firebaseConfig);
} else {
  firebase.app(); // if already initialized, use this one
}


#Firebase Hosting
npm install -g firebase-tools

firebase login
firebase init

npm run build
firebase deploy
#OR (with optional comment)
firebase deploy -m "Deploying the best new feature ever."
```

# Server Side Packages

## Dependencies:
```bash
npm init --yes
npm i express mongodb mongoose cors body-parser dotenv

```

## Dev Dependencies:
```bash
npm i --save-dev nodemon
```
