# Component-Hierarchy-DIagram![Component Hierarchy Diagram](https://user-images.githubusercontent.com/33495426/176185025-4c61fc57-b752-471a-824c-cc4fc617d240.jpg)
Managing state and props in the application:-
1. The parent component that is game will hold all the props and state of the application.
2. It will then pass the props as required by the children i.e. gameboard and cells.
3. setState will take an updater fn which will be updating the state.
4. React will decide when to render this update and it will do it in batches.
