# Restaurant Bill Calculator

This program is a *Restaurant Bill Calculator* that will total up a bill including state tax and tip.

1. It has one input box to enter the cost of the meal
2. It has a select box for the State
3. It has a select box for the tip amount
4. It displays the values of each and the total afterwards

[State Tax Amounts](https://taxfoundation.org/state-and-local-sales-tax-rates-2016/)

```javascript
 bc.tip_options = [
                        {amount:0.10, name:"10%"},
                        {amount:0.15, name:"15%"},
                        {amount:0.20, name:"20%"},
                    ];
                    
                    bc.tip = bc.tip_options[0];
```