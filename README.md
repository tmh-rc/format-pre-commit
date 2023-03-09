# Format Pre-commit

Automate format PHP, JavaScript, HTML, Blade whenever git commit. Support Laravel framework.

### Installation

Download this code to your project.

Install PHP dependences [Pint](https://github.com/laravel/pint):

```
composer install
```

Install Node dependences [Prettier](https://prettier.io) and [blade-formatter](https://github.com/shufo/blade-formatter)

```
npm install
```

Copy `pre-commit` file into `.git/hooks` directory:

```
cp pre-commit .git/hooks/pre-commit
```
