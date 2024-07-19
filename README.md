# Ping CRM: Rails + React

A demo application to illustrate how [Inertia.js](https://inertiajs.com) works with [Rails](https://rubyonrails.org) and [React](https://react.dev).

> This is a port of the [Ping CRM React](https://github.com/liorocks/pingcrm-react) written in Laravel and React.

## Installation

Clone the repo locally:

```sh
git clone https://github.com/skryukov/pingcrm-rails-react.git
cd pingcrm-rails-react
```

Setup (install dependencies, create and seed database):

```sh
bin/setup
```

Start it:

```
bin/dev
```

You're ready to go! Visit Ping CRM in your browser (http://localhost:3000), and login with:

- **Username:** johndoe@example.com
- **Password:** secret

## Running tests

To run the Ping CRM tests, run:

```
bin/rspec
```

## Requirements

- Ruby 3.3
- Ruby on Rails 7
- SQLite

## Credits

- Original work by Jonathan Reinink (@reinink) and contributors
- Port to Ruby on Rails by Georg Ledermann (@ledermann)
- Port to React by Lio (@liorocks)
