# HooBank

A modern bank website built with **React.js** and **Tailwind CSS**.

## Features

- Responsive, mobile-first design
- Modular React components
- Utility-first styling with Tailwind CSS
- Dynamic content via configuration files
- Modern build tooling with Vite

## Project Structure

```
.
├── public/
│   └── hoobank.svg
├── src/
│   ├── assets/         # Images and SVGs
│   ├── components/     # React components
│   ├── constants/      # Static data (links, features, etc.)
│   ├── App.jsx         # Main app component
│   ├── index.css       # Tailwind and global styles
│   ├── main.jsx        # Entry point
│   └── style.js        # Shared style objects
├── index.html
├── package.json
├── tailwind.config.cjs
├── postcss.config.cjs
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or newer)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/hoobank.git
   cd hoobank
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

4. **Open [http://localhost:5173](http://localhost:5173) in your browser.**

### Build for Production

```sh
npm run build
# or
yarn build
```

### Preview Production Build

```sh
npm run preview
# or
yarn preview
```

