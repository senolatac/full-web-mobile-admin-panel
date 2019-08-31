# Product Management System And Admin Panel, Spring Boot, Ionic, Angular 7, MySQL, Hibernate, Liquibase

The application structure is as follows.
- **server-product-management** - Microservice implemented using Spring boot. [More info](server-product-management/README.md)
- **client-product-management** - A NodeJs application implemented using Angular 7. This consumes services hosted by server side.  [More info](client-product-management/README.md)
- **mobile-side** - A NodeJs application implemented using Ionic. This consumes services hosted by server side.  [More info](mobile-side/README.md)

### Build

#### 1) Build Server Side
   
```
$ cd server-product-management
$ gradlew bootJar
$ gradlew bootRun
```

#### 2) Build and run client side

```
$ cd client-product-management
$ ng serve
```

#### 3) Build and run mobile side

```
$ cd mobile-side
$ ionic serve
```

### Access server side using following URL

```
http://localhost:8080
```

### Access client application using following URL

```
http://localhost:4200
```

### Access mobile application using following URL

```
http://localhost:8100
```
