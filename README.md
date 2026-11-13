# 👤 React Authentication Flow

Login and profile pages in **React** that authenticate against the **DummyJSON auth API**, store the token, and use **React Router** for navigation.

## ✨ Features
- `POST /auth/login` request with the Fetch API
- JWT token and user ID saved in `localStorage`
- Navigate to a profile page after login; profile data fetched using the stored user ID
- Error handling for failed logins

## 🛠️ Tech stack
`React` · `React Router` · `REST API` · `localStorage`

## 🚀 Run locally
```bash
npm install
npm start
```
Test credentials are available in the [DummyJSON docs](https://dummyjson.com/docs/auth).
