# Laravel Formatter Pre-commit

Here is formatter config to format before commit. Support following languages and framework
- PHP
- Blade
- HTML
- JavaScript
- Vue.js
- React.js

### Prerequisites
Before getting started, ensure that you have the following installed on your system:

- PHP 8 or higher
- Laravel 8 or higher
- Node.js
- NPM

### Installation

- Download this code in your machine.
- remove `.gitignore`, `README.md` file and `.git` folder
- Move all files into your project
- Install Node dependences [Prettier](https://prettier.io) and [blade-formatter](https://github.com/shufo/blade-formatter)
```
npm install blade-formatter prettier
```

Copy `pre-commit` file into `.git/hooks` directory:

```
cp pre-commit .git/hooks/pre-commit
```
