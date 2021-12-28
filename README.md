# nestjs

## Installing NestJs CLI

```sh
$ npm i -g @nestjs/cli
$ nest -v
```

## Task Management Application

- AppModule (root)
    - TasksModule
        - TasksController
        - TaskEntity
        - TasksService
        - TaskRepository
        - StatusValidationPipe
        - ...
    - AuthModule
        - AuthController
        - UserRepository
        - AuthService
        - JwtStrategy
        - UserEntity
        - ...

### API Endpoint - Tasks

GET

- tasks/ : Get Tasks (incl. filters)
- tasks/:id/ : Get a Tasks

POST

- tasks/ : Create a Task

DELETE 

- tasks/:id/ : Delete a task

PATCH

- tasks/:id/status/ : Update task status