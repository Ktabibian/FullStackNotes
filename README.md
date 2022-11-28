# FullStackNotes
Chapter 1
1) (Project Object Method) pom.xml file holds basic information of the project and dependencies
2) Springboot Initializr can be used to set up a project with dependencies, version types, project type, and language preferance
3) Loggers can be used to capture errors when running a program
4) 7 logging levels: TRACE, DEBUG, INFO, WARN, ERROR, FATAL, OFF
5) Logging levels are set in the application.properties file

Chapter 2
1) Dependency Injection (DI) is used for creating objects that depend on other objects
2) DIs allow classes to interact while maintaining independance
3) Three DI Class Types: service(a class that can be used, is a dependency), client(is a class that uses dependencies), injector(passes dependencies to client)

Chapter 3
1) JPA annotation @Entity is used to make an entity class
2) JPA creates a database table by the class name
3) @Table annotation in the entity class can rename the table
4) Entity class must have a primary key attribute defined by @Id annotation
5) @GeneratedValue annotation creates a unique value for primary key
6) Annotating multiple attributes with @Id creates a composite primary key
7) Entity tables columns are named after the class attributes
8) @Column annotation can be used to define length and if the column is nullable
9) CrudRepository used for basic CRUD functions (Create, Read, Update, Delete)
10) CrudRepository is extended in an entity's relates interface
11) CrudRepository requires a class and id type <ClassName, IdType>
12) @Autowired annotation is used to enable dependency injection
13) @Query annotation is used to create an SQL statement
14) Query staements should be written in the crud repository
15) @OneToMany annotation creates a relationship with one object to many of that object type
16) @ManyToOne annotation is sister to @OneToMany allowing multiple of an object type to belong to a single object
17) FetchType is used for pojo associations
18) toMany relation defaults to FetchType.LAZY
19) FetchType.LAZY used to only fetch the many when needed
20) FetchType.EAGER fetches all associated objects
21) Cascade attribute of @oneToMany defines the effects of updates and deletes on associated entities
22) @ManyToMany relationship creates a relationship of many objects to many objects

Chapter 4
1) 
