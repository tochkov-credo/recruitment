## Web Development API Task

The task is to create an API to manage a user persistence layer. You are free to use the tools and technologies you feel most confident with and that will present your work in the best possible light.

Your solution _must_:

- Expose a **user** model having the following attributes:
  - **`id`** - _a unique user id_
  - **`email`** - _a user's email address_
  - **`firstName`** - _the user's first name_
  - **`lastName`** - _the user's last name_
  - **`createdAt`** - _the date and time the user was added_
- Have the ability to persist user information for at least the lifetime of the test.
- Expose functionality to create, read, update and delete (CRUD) users.
- Be easily consumable by a plain HTTP client e.g. cURL or Postman

If you feel like you want to show us what you're are really capable of, here is a list of potential enhancements that we have come up with. You can always go the extra mile and do not limit yourself to it if you think of any other possible feature enhancement that you want to include in your submission.

- Provide a way for your API to be easily tested/consumed (e.g. a custom front-end, a [Postman](https://www.getpostman.com/) collection or a [Swagger/OpenAPI](https://swagger.io/) API specification).
- Use of an industry standard data exchange format.
- Sanitisation checks of inputs.
- Implementation of test coverage.
