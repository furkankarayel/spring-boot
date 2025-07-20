# List of Spring Data JPA Annotations

| Annotation         | Description |
|--------------------|-------------|
| `@Entity`          | Specifies that the class is an entity and is mapped to a database table. |
| `@Id`              | Specifies the primary key of an entity. |
| `@GeneratedValue`  | Provides the specification of generation strategies for the values of primary keys. |
| `@Table`           | Specifies the primary table for the annotated entity. |
| `@Column`          | Specifies the mapped column for a persistent property or field. |
| `@OneToOne`        | Defines a one-to-one association between two entities. |
| `@OneToMany`       | Defines a one-to-many association between two entities. |
| `@ManyToOne`       | Defines a many-to-one association between two entities. |
| `@ManyToMany`      | Defines a many-to-many association between two entities. |
| `@JoinColumn`      | Specifies a column for joining an entity association or element collection. |
| `@JoinTable`       | Specifies the mapping of associations. |
| `@MappedSuperclass`| Specifies that the class is a mapped superclass. |
| `@Embeddable`      | Specifies a class whose instances are stored as an intrinsic part of an owning entity and share the identity of the entity. |
| `@Embedded`        | Specifies a persistent field or property of an entity whose value is an instance of an embeddable class. |
| `@Transient`       | Specifies that the property or field is not persistent. |
| `@Query`           | Declares finder queries directly on repository methods. |
