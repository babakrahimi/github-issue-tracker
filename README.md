# GitHub Issue Tracker

This project is a simple GitHub issue tracker built with React and TypeScript. It helps users manage GitHub issues efficiently.

## Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Prerequisites

- Node.js (Recommended: LTS version)
- Yarn or npm

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/github-issue-tracker.git
   cd github-issue-tracker
   ```

2. Install dependencies:

   ```sh
   yarn install
   # or
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Copy the contents from `.env.example`:
     ```sh
     cp .env.example .env
     ```
   - Open `.env` and replace `your_github_access_token_here` with your actual GitHub API token.

4. Start the development server:
   ```sh
   yarn start
   # or
   npm start
   ```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

## Environment Variables

| Variable              | Description                                      | Default Value                   |
| --------------------- | ------------------------------------------------ | ------------------------------- |
| `GITHUB_ACCESS_TOKEN` | Your GitHub API access token                     | `your_github_access_token_here` |
| `GITHUB_API_URL`      | GitHub API base URL                              | `https://api.github.com`        |
| `NODE_ENV`            | Environment mode (`development` or `production`) | `development`                   |
| `PORT`                | Port to run the server                           | `3000`                          |

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
