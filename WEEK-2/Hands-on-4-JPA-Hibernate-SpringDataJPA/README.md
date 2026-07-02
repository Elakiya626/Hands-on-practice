# Hands-on 4
# Difference between JPA, Hibernate and Spring Data JPA


## Java Persistence API (JPA)

- JPA is a specification for persisting, reading and managing data from Java objects.
- It defines rules and interfaces.
- It does not contain implementation.
- Hibernate is one implementation of JPA.


Example:

Entity:

```java
@Entity
public class Employee {

    @Id
    private Integer id;

    private String name;

}