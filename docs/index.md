# Capstone
[GitHub Repo](https://github.com/d-sedano/capstone-project-group-3)
### Functional Overiew
- This application performs backend functions of an ecommerce website, connecting the SQL database to the microservice components of the website frontend.
### Implementation
- Recieves a JSON object in the format of the object to be updated in the database, then carries out the update. 

  - user/update/userId - Updates registraion details for given user

  - role/get/id - Returns the role assigned to a given user
### Type
- Component
### Description
- Communicates with the repository with get and set commands
### Methods
- user_update(integer userId) - Updates registraion details for given user
### 
- role_get(id) - Returns the role assigned to a given user
