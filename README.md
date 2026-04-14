# Lifecycle Playground

A mini learning project for understanding **component lifecycle** in React.

## About

This project was built while following the Udemy course **[Modern React From The Beginning](https://www.udemy.com/course/modern-react-from-the-beginning/)**. It explores how React components go through different lifecycle phases — **mounting**, **updating**, and **unmounting** — by logging messages at each stage.

A toggle button mounts and unmounts a logger component from the DOM, making it easy to observe the lifecycle in action via the browser console.

The same behavior is implemented in two ways:

1. **Class Component** (`LifecycleLoggerClass`) — Uses traditional lifecycle methods (`componentDidMount`, `componentDidUpdate`, `componentWillUnmount`) to demonstrate how React class components handle each phase.
2. **Functional Component** (`LifecycleLogger`) — Uses the `useEffect` hook to achieve the same lifecycle logging, showing the modern approach.

The class component version is done first because class lifecycle methods map directly to each phase, giving a clearer mental model before translating the same concepts into hooks.

## 🌐 Live Demo

**➡️ [View Live App](https://dikidikay-lifecycle-playground.netlify.app/)**

## Getting Started

```bash
# Install dependencies
npm install

# Start the dev server
npm run dev
```

## Built With

- [React](https://react.dev/)
- [Vite](https://vite.dev/)
