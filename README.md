# ReqRes API Testing

Postman collection with automated tests for the [ReqRes](https://reqres.in) REST API.

## What's covered

**Users**
- List all users, get a single user, user not found
- Create a user (POST)
- Update a user, both PUT and PATCH
- Delete a user

**Auth**
- Register (valid user, missing password, unknown user)
- Login (valid credentials, missing email, missing password)

**Resources**
- List all resources, single resource, resource not found

**Other**
- Delayed request, for checking how tests handle slower responses

## Running it

1. Clone this repo
2. Open Postman and import `Collections/ReqRes-collection.json`
3. Import `Enviroments/ReqRes-environment.json` as well
4. Select "ReqRes Enviroment" from the environment dropdown (top right)
5. Run individual requests, or the whole collection with the Runner

Note: the `x-api-key` value in the environment file is a placeholder. If ReqRes requires one for certain endpoints, add your own key there.

