# twitch-result-counter

## Requirements

- Firebase project
  - [get config from project setting](https://support.google.com/firebase/answer/7015592?ref_topic=6400762) and put it into `.env`

## Run dev server

- `npm run start`
  - patch [this](https://github.com/facebook/create-react-app/pull/10706) to enable HMR using emacs

## Deploy

### Deploy All

- `npm run build`
- `npx firebase deploy`

### Deploy only firestore rules

- `npx firebase deploy --only firestore:rules`
