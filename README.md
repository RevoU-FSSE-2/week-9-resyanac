
![RESYANA CAHYANITA](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/a58304cf-b3d5-42ca-9f00-571331421b70)


# INTRODUCTION

Hello, Resya here! 23 years old girl in +8 GMT (East Borneo) timezone. I am a Tax Collector and software engineer. The 9th assignment are assigned to a simple API server about mbanking app. 


# Simple Mobile Banking App API

the Simple Mobile Banking App API allows users to retrieve, create, update, and delete transactions in their account. The API is designed to interact with a MySQL database using DBeaver and is built using Node.js.

## Prerequisites

- [Node.js](https://nodejs.org/) .
- [DBeaver](https://dbeaver.io/).
- MySQL database configured and running.
- Basic knowledge of RESTful APIs and SQL.


## API Endpoints

### Get User's Total Balance

- **Endpoint**: `GET /user/:userId`
- **Description**: Retrieve the total balance of a user by summing up their income and subtracting their expenses.
- **Parameters**:
  - `userId` (integer): The ID of the user for whom you want to retrieve the balance.

### Get All Transactions for a User

- **Endpoint**: `GET transactions/:userId`
- **Description**: Retrieve all transactions for a specific user.
- **Parameters**:
  - `userId` (integer): The ID of the user for whom you want to retrieve transactions.

### Create a New Transaction

- **Endpoint**: `POST /transaction/:id`
- **Description**: Create a new transaction for a user. 


### Delete a Transaction

- **Endpoint**: `DELETE //transaction/:id`
- **Description**: Delete an existing transaction by its ID.

## Usage Examples

Here are some usage examples of the API:

- To retrieve the all users:
![Screen Shot 2023-08-19 at 03 51 46](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/eec930e9-f2d4-4c3c-a270-c4d2415f1d07)




- To retrieve the total balance of a user:
![Screen Shot 2023-08-19 at 03 51 40](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/0ebb2d1b-a8ab-40ec-a3df-473d8d636ad5)




- To retrieve all transactions :

![Screen Shot 2023-08-19 at 03 51 30](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/a99617d4-97e2-48f8-b263-6f205eb0a72f)

- To create a new transaction:
![Screen Shot 2023-08-19 at 03 51 35](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/770045fa-22f0-4398-9b46-c398b620f1dc)



- To update a transaction:
![Screen Shot 2023-08-19 at 03 51 23](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/7dcd8f09-63e0-4df0-b8fd-228e9067005f)



- To delete a transaction:
![Screen Shot 2023-08-19 at 03 11 35](https://github.com/RevoU-FSSE-2/week-9-resyanac/assets/135514670/ab89758f-5085-4514-afa6-09929d6cd760)



## Deployment
i deployed this using 


## Conclusion

This Simple Mobile Banking App API provides basic functionality for managing user accounts and transactions. You can use the provided endpoints to retrieve account balances, view expenses, create new transactions, update existing transactions, and delete transactions. Make sure to secure your API endpoints and implement proper authentication and authorization mechanisms in a production environment.
