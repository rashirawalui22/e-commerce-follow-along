### Milestone 25 📝

- An API endpoint was created to receive product details, user email, and address.
- The user ID is retrieved using the provided email.
- Separate orders are stored for each product with the same address in the MongoDB orders collection.
- The implementation follows the existing order schema and ensures data integrity.


### Milestone 26 📝

- An API endpoint was created to receive the user's email.
- The user ID is retrieved using the provided email.
- Using the retrieved _id, all orders associated with the user are fetched.
- The response contains all orders belonging to the user.