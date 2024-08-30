### NPM Commands
For test coverage:  npm test -- --coverage --watchAll=false

For running Linter:  npm run lint

For formatting:  npm run format

Before starting the UI: nvm use 14.15.4

### For dependency tree:
npm list [dependency]

### For checking security vulnerabilities:
npm audit

### for checking current/latest version of installed packages
npm outdated (lists all) or npm view {pkg} version (list one)

For reinstalling package-lock.json:
rm -rf package-lock.json node_modules && npm install

### to run one file at a time
npm test -- {path to test file} 

