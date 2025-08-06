# React Complete Guide - Tic Tac Toe Project

This project is part of the **"React - The Complete Guide (incl Hooks, React Router, Redux)"** Udemy course. It demonstrates essential React concepts through building a Tic Tac Toe game.

## Key Learning Points

### 1. **Component-Based Architecture**
- Breaking the UI into reusable components (`GameBoard`, `Player`, `Log`, `GameOver`).
- Passing data and functions between components via props.

### 2. **State Management**
- Using `useState` to manage game state (board, turns, players).
- Lifting state up to parent components for shared logic.
- Deriving state (e.g., active player, winner, draw) from existing state.

### 3. **Immutability**
- Creating new arrays/objects instead of mutating existing state.
- Using array methods like `map` and the spread operator for updates.

### 4. **Event Handling**
- Handling user interactions (clicking squares, changing player names).
- Passing event handler functions as props.

### 5. **Conditional Rendering**
- Showing/hiding components based on game state (e.g., displaying `GameOver` when the game ends).

### 6. **Derived State & Utility Functions**
- Using helper functions to derive the active player, winner, and game board from turns.
- Keeping logic separate for clarity and reusability.

### 7. **Props vs State**
- Understanding when to use props (for data passed from parent) and when to use state (for local component data).

### 8. **React Best Practices**
- Keeping components small and focused.
- Avoiding unnecessary re-renders.
- Using keys for lists.

## How to Run

1. Install dependencies:
   ```
   npm install
   ```
2. Start the development server:
   ```
   npm start
   ```

## Course Link

[React - The Complete Guide (incl Hooks, React Router, Redux)](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)

---

**Enjoy learning React!**
