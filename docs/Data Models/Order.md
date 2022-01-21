# Order

### Description
The Order Data Model refers to the Order Collection which holds all of the orders 
that have been placed.


### Model
```ts
interface IOrder {
    id: string;
    owner: string;
    created: timestamp;
    startedAt: timestamp|null;
    madeBy: string| null;
    completed: boolean;
    drinkInfo: IDrinkInfo[]
    
}
```
---
### Considerations 
