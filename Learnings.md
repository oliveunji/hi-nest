# 2023-01-13

- mapped-types 패키지 설치 이유: transform your types and mapped types build by nest js developers

- nest g mo: 모듈 생성하는 cli, App js에 있던 서비스와 컨트롤러를 -> movies 모듈 생성하고 -> 그 안으로 집어넣어서 코드 깔끔하게 함

- nest g co: 컨트롤러 생성하는 cli, App 레벨의 컨트롤러를 생성

- nest.js 는 express 기반으로 만들어졌지만, 이거를 fastify 기반으로 바꿀 수 있음. 다만 코드 구현을 express에서만 동작하는 함수로 작성하면 나중에 바꾸기 어렵기 때문에 nest js기반 표현식을 써서 만드는게 좋다.

# Design Patterns Used in Nest.js
Nest.js is a web framework built on top of Node.js that uses TypeScript and follows the architecture patterns of Angular. Some common design patterns used in Nest.js include:

1. MVC (Model-View-Controller): Nest.js implements the MVC pattern, which separates an application into three main components: models, which represent the data; controllers, which handle the logic and communication between the model and the view; and views, which handle the presentation of the data.

1. Dependency Injection: Nest.js makes use of the dependency injection design pattern, which allows for the automatic injection of required dependencies into a class or component. This makes it easy to swap out different implementations of a service or to mock a service for testing.

1. Decorators: Nest.js makes use of TypeScript decorators, which are a way to add metadata to a class or its members. Decorators are used in Nest.js to define controllers, routes, pipes, providers, and guards.

1. Pipes: Nest.js uses pipes to validate and transform data before it reaches a controller or a service. Pipes can be used to perform tasks such as validation, sanitization, and data transformation.

1. Guards: Nest.js uses guards to protect routes and control access to them. Guards can be used to check whether a user is authenticated or authorized to access a certain route.

1. Interceptors: Nest.js uses interceptors to handle cross-cutting concerns, such as logging, error handling, and request/response transformations.

1. Providers: Nest.js uses providers to create services and make them available to the application. Providers can be used to create singleton instances of a service or to create a new instance of a service for each request.

These are just a few examples of the design patterns that are commonly used in Nest.js, but there are many other patterns and techniques that can be used to build scalable and maintainable applications.
