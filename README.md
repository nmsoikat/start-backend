# Start Front-End
```bash
# react app
npx create-react-app myApp

# install bootstrap and router
npm i bootstrap reactstrap react-router-dom

#implement bootstrap
import 'bootstrap/dist/css/bootstrap.min.css';
import { Button } from 'reactstrap';

# install font-awesome
npm i @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/react-fontawesome

# implement font-awesome
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faCoffee } from '@fortawesome/free-solid-svg-icons'
const element = <FontAwesomeIcon icon={faCoffee} />

```


# Server Side Packages

## Dependencies:
```bash
npm init --yes
npm i express mongodb mongoose cors body-parser dotenv

#Firebase
npm i firebase

#Firebase Hosting
npm run build
firebase deploy
#OR (with optional comment)
firebase deploy -m "Deploying the best new feature ever."
```

## Dev Dependencies:
```bash
npm i --save-dev nodemon
```