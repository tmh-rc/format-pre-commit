# Formatter Pre-commit

Here is formatter config to format before git commit. Support following languages and framework
- PHP [(Pint)](https://github.com/laravel/pint)
- Blade [(blade-formatter)](https://github.com/shufo/blade-formatter)
- HTML [(Prettier)](https://prettier.io)
- JavaScript [(Prettier)](https://prettier.io)
- Vue.js [(Prettier)](https://prettier.io)
- React.js [(Prettier)](https://prettier.io)

## Prerequisites
Before getting started, ensure that you have the following installed on your system:

- PHP 8 or higher
- Laravel 8 or higher (for Laravel project)
- Composer 2
- Node.js
- NPM

## Installation

- Download this code in your machine.
- remove `.gitignore`, `README.md` file and `.git` folder
- Move all files into your project under root directory
- Install Node dependences [Prettier](https://prettier.io) and [blade-formatter](https://github.com/shufo/blade-formatter)
```
npm install blade-formatter prettier
```
- **(No need for Laravel)** Install PHP dependences [Pint](https://github.com/laravel/pint):
```
composer require laravel/pint --dev
```
Copy `pre-commit` file into `.git/hooks` directory:
```
cp pre-commit .git/hooks/pre-commit
```
