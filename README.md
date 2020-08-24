## Versiones
* Ruby 2.6.0
* Rails 6.0.2.1
* Yarn 1.21.1
* Nodejs 10.14.1

## Instalación

`bundler install`: Instalar gemas.
`yarn install`: Instalar paquetes js.

### Masterkey
Solicitar la key del proyecto y crear el archivo `config/master.key`

### Base de datos
* PostgreSQL

Para crear la base de datos:
```
rails db:create
rails db:migrate
rails db:seed
```

## Ejecución
Para la ejecución del proyecto se debe tener instalado `overmind` y ejecutar el siguiente comando:

```
overmind start
```

## Test
El proyecto utiliza `rspec 3.9`. Para correr los test:
```
rspec .
```

## Deploy
