# eslint-config-blueai
A custom ESLint configuration for modern JavaScript and TypeScript projects, with React support.

## URL 
https://www.npmjs.com/package/eslint-config-blueai

## Features

- Base configuration extends from ESLint recommended settings
- TypeScript support with @typescript-eslint/recommended rules
- React-specific linting rules
- Customized rules for code style consistency

## Installation
You can install this package using npm:
```bash
npm install --save-dev eslint eslint-config-blueai
```

## Usage
After installing the package, add it to your .eslintrc.js file:
```js
module.exports = {
  extends: ['eslint-config-blueai'],
};
```

Or if you're using a .eslintrc.json file:

```json
{
  "extends": ["eslint-config-blueai"]
}
```

## Customization
You can override or extend the rules in your own ESLint configuration file. For example:
```js
module.exports = {
  extends: ['eslint-config-blueai'],
  rules: {
    // Your custom rules here
    'no-console': 'warn',
  },
};
```

## Key Rules
This configuration includes the following notable rules:

- indent: 2 spaces
- linebreak-style: Unix
- quotes: Single quotes
- semi: Always use semicolons
- no-unused-vars: Warn about unused variables
- react/prop-types: Turned off (assumes use of TypeScript for prop validation)

For a full list of rules, please refer to the .eslintrc.js file in this package.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
