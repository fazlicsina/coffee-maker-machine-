# OOP Coffee Machine

A command-line coffee machine simulator built with Python and object-oriented programming. It offers a small drink menu, checks ingredient resources, processes coins, and dispenses drinks with change.

## Features
- Menu with espresso, latte, and cappuccino
- Resource tracking for water, milk, and coffee
- Coin-based payment with change
- Simple CLI loop (`report`, `off`, or choose a drink)

## How To Run
1. Make sure you have Python 3 installed.
2. Run:

```bash
python3 main.py
```

## Project Structure
- `main.py` - entry point and main loop
- `coffee_maker.py` - resource tracking and brewing logic
- `menu.py` - menu items and lookup
- `money_machine.py` - coin handling and payment logic

## Example Session
```
what would you like? (latte/espresso/cappuccino)
latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $0.0 in change.
Here is your latte ☕️. Enjoy!
```

## Notes
- Type `report` to see remaining resources and money.
- Type `off` to stop the program.
