# universal-react-template

### Set Up

1. Install wml

2. Set up the common package for web package by doing following steps:

- Go to the web package: `cd workspaces/web`
- `wml add ../common ./node_modules/@universal/common`

3. Set up the common package for app just like we did for the web package:

   - Go to the web package: `cd workspaces/app`
   - `wml add ../common ./node_modules/@universal/common`

4. `wml start`

### Start Projects

- web: `yarn start`
- app: `yarn start` then `yarn ios` or `yarn android`
