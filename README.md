# React 19 useEffect Performance Issue

This repository demonstrates a common performance issue in React 19 applications related to the `useEffect` hook. The original code causes unnecessary re-renders because the `useEffect` hook lacks an optimized dependency array. The solution shows how to fix this using the correct dependencies.