# project-plan
Generic thoughts on project development

- Log all user specific activities (without sensitive data) for future reports, charts, analytics
- Use Bus (RabbitMQ, ActiveMQ)
- Store data for each tenant (company) in separate stores
- Build pieces as microservices
- Don't split into microservices too early
- Write e2e tests, integrational, test services independently
- Log app messages to persistent storage (so you can analyze them later)
- Separate REST API from Data Layer, talk to Data over Queue
- Practice Definition Driven Development (write contracts between your microservices at first)

## Scaling
- Think how would you scale
- Autoscaling
- Monitoring
- Provisioning
- Health checking
- Distribution
- Check tools (Docker, Kubernetese)

## REST API
- Design REST API beforehand (RAML, Swagger) 
- Validate your API against RAML, show gaps on both sides (missed definition or missed functionality)
- Validate schemas (JSON schemas for definition)
- Write examples

## Queue API
- Design Queue API (TBD: tools)
- Validate schemas
- Write examples

## Authorization (permissions, roles)
- Design it early

## Tools
- Invest time in trying tools, reading books on proper leveraging tools (Go, Mongo, Postgres, Express, Koa, Angular, React, D3)
