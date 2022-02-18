# Introduction
- Basic REST based application, based on `Spring` and `Hibernate`. 
- This project uses `exception handling` to return the errors in JSON format. 
- Project provides api's to access Customer details. 
- Various allowed APIs include 
- These APIs can be tested using POSTMAN or BROWSER itself. 

## APIs
|HTTP Method| Endpoint |CRUD Action|
|-----------|----------|-----------|
|POST| /api/customers| Create a new customer|
|GET |/api/customers |Read a list of customers|
|GET |/api/customers/{customerId}| Read a single customer|
|PUT |/api/customers |Update an existing customer|
|DELETE| /api/customers/{customerId} |Delete an existing customer|
