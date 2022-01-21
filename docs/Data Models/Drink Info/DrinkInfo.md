w# Drink Info

### Description
Drink Info contains all of the data needed for
a server to make a drink.

### Model

```ts
interface IDrinkInfo {
    base: "MilkTea"| "FruitTea";
    toppings: ITopping[];
    
    
}
```



---
### Considerations

From the meeting, it seems that drinks have either a milk tea or fruit tea base. This may
theoretically change in the future so it could be helpful to have a specified **base** field.

To reduce type related issues it could be helpful to strongly type the fields and remove generic strings.



