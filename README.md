# InstaDeep FE Interview Tasks

## Task 1

- Custom map, filter and reduce functions implementations

```js
const listOfPeople = [
  { name: "AO", age: 50 },
  { name: "ZO", age: 40 },
  { name: "SE", age: 30 },
];
```

- [ ] Add profession property to listOfPeople array, knowing that AO and ZO are Software Engineers and SE is a Data Scientist.
- [ ] Create a filtered subset of individuals from the listOfPeople array who are in their forties.
- [ ] Compute the average age of the individuals in the listOfPeople array.

## Task 2

![image](https://github.com/chemsseddine/instadeep-interview-tasks/assets/6200384/c4b70ad5-9ede-454b-a559-fc5bfa9a0ff2)

Develop a Store API to manage the state of your application. The store acts as the central repository for application data. When the view dispatch or triggers an action, it communicates with the reducer to update the app's data in the store. The reducer is a pure function that reads the action's instructions and generates a new version of the app's data based on the original state.

- [ ] Implement the Create Store API
- [ ] Conduct an Integration Test for the createStore API
- [ ] Demonstrate its functionality using the provided index.html file to simulate the usage.

## Task 3

- implement useState and useEffect hooks from scratch
