# 🤖 Reddit Client

This is a **Reddit client application** built with React to browse Reddit posts. The project leverages the **Reddit API** to fetch and display content from various subreddits. It's built as a single-page application and uses **Redux** and **Redux Toolkit** for efficient state management.

-----

## 🚀 Features

  * **Browse posts**: View top posts from different subreddits.
  * **Search functionality**: Find specific subreddits and posts.
  * **Interactive UI**: A clean and responsive user interface for a smooth browsing experience.
  * **State management**: Uses Redux Toolkit to manage application state, including posts, search queries, and loading status.

-----

## 🛠️ Tech Stack

  * **Frontend**: React
  * **State Management**: Redux, Redux Toolkit
  * **API**: Reddit API

-----

## 📂 Project Structure

```
reddit-client/
│
├── public/                 # Static assets
├── src/
│   ├── api/                # API calls
│   │   └── reddit.js       # Reddit API requests
│   ├── components/         # Reusable React components
│   │   ├── Card/
│   │   │   ├── Card.css
│   │   │   └── Card.jsx
│   │   ├── features/
│   │   │   ├── Avatar/
│   │   │   ├── Comment/
│   │   │   ├── Header/
│   │   │   ├── Home/
│   │   │   ├── Post/
│   │   │   ├── PostLoading/
│   │   │   └── Subreddits/
│   ├── store/              # Redux store and slices
│   │   ├── index.js        # Store configuration
│   │   ├── redditSlice.js  # Slice for posts and search
│   │   └── subRedditSlice.js # Slice for subreddits
│   ├── utils/              # Helper functions
│   │   ├── getRandomNumber.js
│   │   └── shortenNumber.js
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── index.jsx
├── .gitignore
├── package.json
└── README.md
```

-----

## ⚙️ Available Scripts

This project was bootstrapped with **Create React App**. In the project directory, you can run the following scripts:

### `npm start`

Runs the app in the development mode. Open [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000) to view it in your browser. The page will automatically reload if you make edits.

### `npm test`

Launches the test runner in interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The app is then ready to be deployed.

-----

## 📚 Learn More

For more information on the tools and technologies used, check out these resources:

  * [**Create React App Documentation**](https://create-react-app.dev/docs/getting-started)
  * [**React Documentation**](https://www.google.com/search?q=https://reactjs.org/docs/getting-started.html)
  * [**Redux Documentation**](https://redux.js.org/)
  * [**Redux Toolkit Documentation**](https://redux-toolkit.js.org/)