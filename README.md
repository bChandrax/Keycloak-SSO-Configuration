this repository has 2 sub folders that used to be their own repos:
Keycloak-app-SSO i'll call this app 1
Keycloak-app-SSO-2 i'll call this app 2

# app 1
  run pnpm i in the root of app 1
## ports used and how to start them
  frontend: 5173: in the root of app 1 run "pnpm dev"
  backend: 3000: in the root of app 1 run "pnpm start"
  makes requests to keycloak at port 8080

# app 2
  run pnpm i in the root of app 2
## ports used and how to start them
  frontend: 5174: in the root of app 2 run "pnpm dev"
  backend: 3001: in the root of app 2 run "pnpm start"
  makes requests to keycloak at port 8080

# docker and keycloak set up
