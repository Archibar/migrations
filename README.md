# Doctrine Database Migrations

## Modifications

Add configuration property for registering Doctrine type mapping from _migrations.yml_.

Example:

    name: Doctrine Migrations
    migrations_namespace: DoctrineMigrations
    table_name: migrations
    migrations_directory: /path/to/migrations
    mapping_types:
        enum: string
        set: string


## Official Documentation

All available documentation can be found [here](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/).

The repository containing the documentation is [there](https://github.com/doctrine/migrations-documentation).


