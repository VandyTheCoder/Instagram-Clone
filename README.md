# Instagram Clone

Just a practice my skill with RubyOnRails 7 with Bootstrap 5 UI.

## Install

### Clone the repository

```shell
git clone git@github.com:VandyTheCoder/Instagram-Clone.git
cd Instagram-Clone
```

### Check your Ruby version

```shell
ruby -v
```

The ouput should start with something like `ruby 3.0.3`

If not, install the right ruby version using [rbenv](https://github.com/rbenv/rbenv) (it could take a while):

```shell
rbenv install 3.0.3
```

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler) and [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Initialize the database

```shell
rails db:create db:migrate db:seed
```

## Serve

```shell
rails s
```