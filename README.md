# [MIDPS Lab #1](https://github.com/emirovschi/MIDPS-1)

This repository contains the work done for first MIDPS Laboratory described [here](https://github.com/BestMujik/MIDPS-labs/blob/midps_fr/MIDPS_LAB%231.md).

## Links

* Repository: https://github.com/emirovschi/MIDPS-1
* Documentation: https://github.com/emirovschi/MIDPS-1/blob/master/Documentation/Lab_template.pdf

## Taks
1. Initialize repository
2. Configure repository
3. Create at least 2 branches
4. Create at least 1 commit for each branches
5. Track remote origin
6. Reset branch to a previous commit
7. Create .gitignore file
8. Merge two branches
9. Resolve a merge conflict
10. Create and view tags

# [MIDPS Lab #2](https://github.com/emirovschi/MIDPS-2)

This repository contains the work done for second MIDPS Laboratory described [here](https://github.com/BestMujik/MIDPS-labs/blob/midps_fr/MIDPS_LAB%232.md). The project reperesents a GUI calculator build in Java with basic operations like +,-,*,/,raise to a specific power,root,sign change (+/-), should support decimal numbers.

## Links

* Repository: https://github.com/emirovschi/MIDPS-2
* Documentation: https://github.com/emirovschi/MIDPS-2/blob/master/Documentation/Lab_template.pdf
* Release: https://github.com/emirovschi/MIDPS-2/tree/master/releases/1.0
* Used IDE: IntelliJ
* Programming language: Java
* Used technologies: Maven, Apache Pivot, jUnit, Mockito

## Taks
1. Implementation of a simple GUI calculator which supports the following operations: +,-,*,/,raise to a specific power,root,sign change (+/-), should support decimal numbers
2. The project should consist of two modules: core - which contains all the logic and gui - which contains all graphic related code

# [MIDPS Lab #3](https://github.com/emirovschi/MIDPS-3)

This repository contains the work done for third MIDPS Laboratory described [here](https://github.com/BestMujik/MIDPS-labs/blob/midps_fr/MIDPS_LAB%233.md). The project reperesents a Java REST API as backend built using Spring framework and a frontend built with AngularJS.

## Links

* Repository: https://github.com/emirovschi/MIDPS-3
* Documentation: https://github.com/emirovschi/MIDPS-3/blob/master/Documentation/Lab_template.pdf
* Release: http://midps3.herokuapp.com/
* Used IDE: IntelliJ
* Programming language: Java, JavaScript
* Used technologies: Maven, Spring Framework, Spring Boot, Spring Data, AngularJS, Angular Material

## Taks
1. Implementation of a website.
2. The website should use a databas
3. The website should contain AJAX requets
4. Implementation of XHR or JSON response. Some of the information should be dynamically loaded on the page.

## Configuration
In order to use different database sources the project requires specific configuration. The following environment variabiles are mandatory for the project to work:
* `JDBC_DATABASE_URL` - Database URL
* `JDBC_DATABASE_USERNAME` - Database user
* `JDBC_DATABASE_PASSWORD` - Dataase password
* `JDBC_DATABASE_DRIVER` - Database dirver. This field depends on the type of database used.
* `JDBC_DATABASE_DIALECT` - Database dialect. This field depends on the type of database used which should be the same used for driver property.

Example:
```
JDBC_DATABASE_URL=jdbc:h2:./database;DB_CLOSE_DELAY=-1;DB_CLOSE_ON_EXIT=FALSE
JDBC_DATABASE_USERNAME=sa
JDBC_DATABASE_PASSWORD=
JDBC_DATABASE_DRIVER=org.h2.Driver
JDBC_DATABASE_DIALECT=org.hibernate.dialect.H2Dialect
```

# [MIDPS Lab #4](https://github.com/emirovschi/MIDPS-4)

This repository contains the work done for fourth MIDPS Laboratory described [here](https://github.com/BestMujik/MIDPS-labs/blob/midps_fr/MIDPS_LAB%234.md). The project reperesents a 3D game for mobiles built using Unity3D platform.

## Links

* Repository: https://github.com/emirovschi/MIDPS-4
* Documentation: https://github.com/emirovschi/MIDPS-4/blob/master/Documentation/Lab_template.pdf
* Release: https://github.com/emirovschi/MIDPS-4/blob/master/Releases/Android/flappy-cube.apk
* Used IDE: Unity Editor, Visual Studio
* Programming language: C#
* Used technologies: Projeny, Zenject

## Taks
1. Implementation of a game
2. The game should be cross platform (can be installed on both Android and iOS)
