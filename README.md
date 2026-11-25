<h1 align="center">Hi 👋, I'm Filipe Campos</h1>
<h3 align="center">Solutions Architect · Web development specialist · AWS</h3>

<p align="center">
  <a href="https://filipercampos.github.io"><b>🌐 Portfolio with interactive demos</b></a> ·
  <a href="https://www.linkedin.com/in/filipercampos">LinkedIn</a> ·
  <a href="mailto:filipecampos123@hotmail.com">filipecampos123@hotmail.com</a>
</p>

I'm a solutions architect, currently in the mobility sector, with a background as a web development specialist. I design systems that must stay correct under concurrency, retries and partial failure. Every project below has its decisions written down as ADRs, tests that prove them (Testcontainers / LocalStack), infrastructure as code, and numbers that were actually measured, including the targets that were not met.

## 🏗️ Portfolio

| Project | What it proves | Stack |
|---|---|---|
| [**ledger-service**](https://github.com/filipercampos/ledger-service) | Double-entry ledger: no lost updates, no duplicate postings, deadlock-free locking, transactional outbox | NestJS · PostgreSQL/Aurora · EventBridge · Cognito · Lambda · ECS Fargate |
| [**platform-infra**](https://github.com/filipercampos/platform-infra) | AWS foundation: VPC, EKS (EC2 + Fargate), GitHub OIDC, hardened Helm chart, SLO burn-rate alerting | CloudFormation · EKS · Helm · OpenTelemetry/ADOT · CloudWatch |
| [**order-saga-platform**](https://github.com/filipercampos/order-saga-platform) | Orchestrated saga with compensations, outbox + inbox dedup, DLQ redrive, CQRS read model | NestJS · SNS/SQS FIFO · PostgreSQL · DocumentDB · EKS |
| [**flash-sale-engine**](https://github.com/filipercampos/flash-sale-engine) | 285k buyers across k6 storms, zero oversell: atomic stock gate, rate limiting, waiting room | NestJS · Redis (Lua) · DynamoDB · SQS · k6 |
| [**serverless-doc-pipeline**](https://github.com/filipercampos/serverless-doc-pipeline) | Multi-tenant ingestion surviving duplicate events and poison files, tenant isolation | AWS SAM · Lambda · S3 · SQS · DynamoDB · Powertools |
| [**legacy-strangler-migration**](https://github.com/filipercampos/legacy-strangler-migration) | SQL Server → PostgreSQL without big-bang: CDC sync, single-writer rule, shadow reads, parity checks | NestJS · SQL Server · Aurora PostgreSQL · CDC |
| [**filipercampos.github.io**](https://github.com/filipercampos/filipercampos.github.io) | The six projects as interactive in-browser demos, PT/EN, light/dark | React · TypeScript · Vite · GitHub Pages |

## 🧰 Core stack

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" title="Node.js" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg" alt="NestJS" title="NestJS" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS" title="AWS" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/microsoftsqlserver/microsoftsqlserver-original.svg" alt="SQL Server" title="SQL Server" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB / DocumentDB" title="MongoDB / DocumentDB" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" title="Redis" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes" title="Kubernetes / EKS" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/helm/helm-original.svg" alt="Helm" title="Helm" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" title="GitHub Actions" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="40" height="40" />
</p>

**AWS:** ECS Fargate · EKS (EC2 + Fargate) · Lambda · SAM · CloudFormation · RDS / Aurora (PostgreSQL, SQL Server) · DynamoDB · DocumentDB · S3 · SQS · SNS · EventBridge · Cognito · CloudWatch · X-Ray · ECR

**Practices:** Event-driven architecture · Saga · Transactional outbox / inbox · CQRS · Idempotency · Strangler fig · CDC · SLOs and burn-rate alerting · OpenTelemetry · ADRs · Threat modeling (STRIDE) · Load testing (k6) · Testcontainers

## 📱 Mobile

Outside the backend, Flutter is my favorite tool: cross-platform apps for Android and iOS from a single Dart codebase.

| Project | What it shows | Stack |
|---|---|---|
| [**vehicle-inspection-checklist**](https://github.com/filipercampos/vehicle-inspection-checklist) | Pre-trip fleet inspection with an interactive 3D damage map: Blender-rendered turntables + per-pixel part map, no 3D engine at runtime | Flutter · Riverpod · go_router · Blender |

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="Flutter" title="Flutter" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="Dart" title="Dart" width="40" height="40" />
</p>

## 🔧 Also worked with

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" title="C#" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt=".NET" title=".NET" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kotlin/kotlin-original.svg" alt="Kotlin" title="Kotlin" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original.svg" alt="Android" title="Android" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ionic/ionic-original.svg" alt="Ionic" title="Ionic" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg" alt="Angular" title="Angular" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="Express" title="Express" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-plain.svg" alt="Firebase" title="Firebase" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azure/azure-original.svg" alt="Azure" title="Azure (App Service, Container Registry)" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg" alt="Google Cloud" title="Google Cloud" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ" title="RabbitMQ" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="Oracle" title="Oracle" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" title="Nginx" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mocha/mocha-original.svg" alt="Mocha" title="Mocha" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" title="Bootstrap" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postman/postman-original.svg" alt="Postman" title="Postman" width="32" height="32" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/xd/xd-original.svg" alt="Adobe XD" title="Adobe XD" width="32" height="32" />
</p>

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/filipercampos)
- [filipecampos123@hotmail.com](mailto:filipecampos123@hotmail.com)
- [Stack Overflow](https://stackoverflow.com/users/3144675/filipecampos)
