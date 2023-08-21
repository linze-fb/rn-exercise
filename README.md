# Creating a Single-Page React Native Application
Manage user profiles with some specific features for a mobile app. Here's what you need to do:

1. **Fetch User**: Implement a fetch function to fetch a user on button click from the provided API and display the profile with the card component.
2. **Header**: Display a header that reads "Welcome to the app, \$USER!".
3. **State Synchronization**: Sync the value of the user's name to the header.
4. **User Card**: Create a card component that displays a user's profile picture, name, email, and phone number.
5. **Swipe to Get New Profile**: Implement a swipe gesture to fetch a new user profile.
6. **Editable Fields**: Allow users to edit the name, email, and phone number via an Edit -> Save button at the bottom of the card. Implement a function to save the edited version to the API, and refresh the data immediately.

API endpoints:
URL: `https://user-workers-demo.alexpear.workers.dev`
Returns a list of user profiles: `GET /users`
Edit user info (email and name): `PATCH /users/:id`