# Redux Contacts

A React Native application for adding and listing contacts using Redux.

## Features

- Add contacts
- View contact list
- Global state management with Redux
- Navigation between screens with React Navigation

## Installation

1. **Clone the project:**
   ```sh
   git clone https://github.com/yourusername/reduxcontacts.git
   cd reduxcontacts
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Start the mobile app:**
   ```sh
   npx react-native run-android
   # or
   npx react-native run-ios
   ```

## Technologies Used

- React Native
- Redux & React-Redux
- React Navigation

## Folder Structure

```
reduxcontacts/
├── App.tsx
├── src/
│   ├── navigators/
│   ├── redux/
│   ├── screens/
│   └── utils/
```

## Notes

- Name and phone number are required when adding a contact.
- Phone number must be at least 11 characters.
- After adding a contact, you will be redirected to the home screen.

## Contribution

Feel free to send a pull request to contribute.

---

