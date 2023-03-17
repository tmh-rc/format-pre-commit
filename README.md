# Laravel Formatter Pre-commit

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
- Laravel 8 or higher
- Composer 2
- Node.js
- NPM

## Installation

- Clone this repo in your machine except working folder
```
https://github.com/tmh-rc/format-pre-commit.git
```
- Go cloned folder
- remove `.gitignore`, `README.md` file and `.git` folder
- Move all files into your laravel project
- Install Node dependences [Prettier](https://prettier.io) and [blade-formatter](https://github.com/shufo/blade-formatter)
```
npm install blade-formatter prettier
```
Copy `pre-commit` file into `.git/hooks` directory:
eg.
```
cp pre-commit .git/hooks/pre-commit
```
- Done
