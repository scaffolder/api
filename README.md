# Scaffolder API

Main point of interaction with Scaffolder aPaaS platform which is heavily used by other components like Scaffolder CLI, Playground, Admin, Dashboard, Workspaces...

## Protocols to be supported

REST + gRPC + GraphQL APIs

## Authentication

```bash
curl --request GET \
--url "https://api.scaffolder.io/v1/login" \
--header "Authorization: Bearer YOUR-TOKEN"
```

## Example calls

```bash
POST /v1/register
POST /v1/login
GET /v1/account
POST /v1/password/reset
GET /v1/projects
GET /v1/projects/project-name/apps
GET /v1/projects/project-name/services
```
