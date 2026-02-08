# Sandwich Machine

A Python-based sandwich vending machine simulator that manages inventory, processes coin payments, and dispenses sandwiches of various sizes.

## Features

- **Three sandwich sizes**: Small ($1.75), Medium ($3.25), and Large ($5.50)
- **Inventory management**: Tracks bread, ham, and cheese resources
- **Coin processing**: Accepts large dollars, half dollars, quarters, and nickels
- **Change calculation**: Returns correct change after purchase
- **Resource checking**: Prevents orders when ingredients are insufficient

## Usage

Run the program:

```bash
python main.py
```

### Commands

| Command | Description |
|---------|-------------|
| `small` | Order a small sandwich |
| `medium` | Order a medium sandwich |
| `large` | Order a large sandwich |
| `report` | Display current inventory levels |
| `off` | Turn off the machine |

### Example

```
What would you like? (small/ medium/ large/ off/ report): small
Please insert coins.
how many large dollars?: 2
how many half dollars?: 0
how many quarters?: 0
how many nickels?: 0
Here is $0.25 in change.
small sandwich is ready. Bon appetit!
```

## Sandwich Recipes

- **Small**: 2 bread, 4 ham, 4 cheese
- **Medium**: 4 bread, 6 ham, 8 cheese
- **Large**: 6 bread, 8 ham, 12 cheese

## Requirements

- Python 3.x
