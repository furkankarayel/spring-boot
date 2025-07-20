# List of Repository Methods

| Method                          | Description |
|---------------------------------|-------------|
| `save`                          | Saves a given entity. |
| `saveAll`                       | Saves all given entities. |
| `findById`                      | Retrieves an entity by its ID. |
| `existsById`                    | Checks whether an entity with the given ID exists. |
| `findAll`                       | Returns all instances of the type. |
| `findAllById`                   | Returns all instances of the type with the given IDs. |
| `count`                         | Returns the number of entities available. |
| `deleteById`                    | Deletes the entity with the given ID. |
| `delete`                        | Deletes a given entity. |
| `deleteAll`                     | Deletes all entities managed by the repository. |
| `deleteAllById`                 | Deletes all instances of the type with the given IDs. |
| `deleteAll(Iterable<? extends T> entities)` | Deletes the given entities. |

## Difference Between `CrudRepository` and `JpaRepository`

- `CrudRepository` is a basic repository interface that provides basic CRUD operations.
- `JpaRepository` extends `CrudRepository` and adds additional JPA-specific methods.
