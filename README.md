# React-Query-Library

## What is React query Library?
It is a powerful **asynchronous state management library** that can be used in JS/Typescript, React, Vue, Solid, and Svelte.

## Why use React Query instead of using useEffect()?
It makes fetching, caching, synchronizing, and updating server state in your React applications a breeze while Making API calls on useEffect() can be error-prone or downright slow. If a component includes the React useEffect() hook, it runs immediately after the component is rendered, and then each time any of its declared dependencies change. To avoid executing useEffect() unnecessarily, we should construct our code so that useEffect() runs only when it is actually needed.


## React query helps to overcome some server state challenges including:
* Caching... (possibly the hardest thing to do in programming)
* Deduping multiple requests for the same data into a single request
* Updating "out of date" data in the background
* Knowing when data is "out of date"
* Reflecting updates to data as quickly as possible
* Performance optimizations like pagination and lazy loading of data
* Managing memory and garbage collection of server state
* Memoizing query results with structural sharing

## How to install it in our project?
for v3 use 
```
  npm i react-query
```
for v4 use 
```
npm i @tanstack/react-query

```

  
