## Installation
```shell
$ yarn create react-app . --template typescript
```

## Deployment
Link: https://dmitrylavrov.github.io/test-cicd-react/

## Hints
Require for Github actions:
```shell
## add to package.json
"homepage": "/test-cicd-react",
```
```shell
## add to .env (use it in routing)
REACT_APP_BASE_URL=/test-cicd-react
```

Error with Permissions-Policy header: Origin trial controlled feature not enabled: 'interest-cohort'.
```html
<!--add to <head> -->
<meta http-equiv="Permissions-Policy" content="interest-cohort=()"/>
```
