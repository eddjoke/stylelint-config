## Stylelint configuration

Slightly customized stylelint configuration based on `stylelint-config-recommended-scss`.

## Installation

1.  Add `.stylelintrc, .stylelintignore` to project root
1.  Run:

```bash
yarn add -D stylelint stylelint-scss stylelint-config-recommended-scss
```

### package.json script

You can add the following script to `package.json` to start using stylelint rightaway:

```json
  "lint:css": "stylelint '**/*.*'",
```
