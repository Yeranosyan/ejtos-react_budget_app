# IBM Full-Stack 2023 Gagik Yeranosyan

## Budget Allocation Application

## In this React Budget Allocation app, I'll learn how to break down a UI into React components. I'll will become familiar with state using the Context API. Furthermore, you will explore actions, reducers, and the dispatch function. I was create a code file, save it, and edit it to make changes.

## Details of the six components:

In Budget.js I'm will be adding text and value for your budget. I'm will be importing app context and the useContext hook, and pass your AppContext to it - this is how a component connects to the context in order to get values from global state.
In Remaining.js I'm was be importing expense and budget from context and getting the remaining value using subtraction.
In ExpenseTotal.js I'm was be adding useContext and AppContext. Taking the expenses from state.
In ExpenseList.js I'm was be using the map function to display the Expenseitem component.
In Expenseitem.js I'm was be importing dispatch from Context, which allows you to dispatch a delete action, creating a function that gets called when the delete icon is clicked.
In AllocationForm.js I'm was creating an expense object, containing the name and the cost. This is what will get dispatched as the payload, and what I'll use to update the state.
![screen-budget](https://github.com/Yeranosyan/ejtos-react_budget_app/assets/120154377/c7d83311-9d56-49d4-8ddd-91011fb212ae)
