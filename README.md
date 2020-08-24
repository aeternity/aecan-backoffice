## Versions
* Ruby 2.6.0
* Rails 6.0.2.1
* Yarn 1.21.1
* Nodejs 10.14.1

## Installation

`bundler install`: Intall gems.
`yarn install`: Install js packages.

### Masterkey
Project key request and create file`config/master.key`

### Data base
* PostgreSQL

Database creation:
```
rails db:create
rails db:migrate
rails db:seed
```

## Ejecution
Must have `overmind` installed and run the following comman:

```
overmind start
```

## Test
To run tests we use `rspec 3.9`  :
```
rspec .
```

## Deploy
