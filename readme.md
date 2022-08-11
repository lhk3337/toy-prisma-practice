# Prisma

- Node.js와 Typescript ORM(Object Relational Mapping)

- Javascript, Typescript <---> DataBase

- SQL같은 데이터베이스 언어로 작성하지 않고, Typescript코드만 작성(타입이 다르면 에러 발생)

schema.prisma파일에 데이터의 형태가 무엇인지 알려주어야 함

Prisma가 데이터의 형태를 알고 있으면 client를 생성함

client을 이용하면 Typescript로 데이터베이스와 직접 상호 작용할 수 있고 또한 자동완성기능 제공

# PlanetScale

The MySQL compatible serverless database platform

MySQL을 사용하는 것이 아니라, MySQL과 호환되는 뭔가를 사용

Developer Experience

    - CLI, git을 쓰는 것처럼 데이터베이스를 다룰 수 있음
    - 데이터베이스에 branch를 만들 수 있고, merge도 할 수 있음

## Vitess

가장 scaling 기능이 뛰어난 오픈소스 데이터베이스
MySQL을 좀 더 쉽게 scaling 할 수 있도록 하는 시스템
특징 : Horizon Scale, High Availability, MySQL Compatible, Online Schema Migrations, Materialized Views, Kubernetes Native
