# Simple Counter - Extended Clarity Contract

A comprehensive Clarity smart contract implementing an extended counter with arithmetic operations, validation, and utility functions for the Stacks blockchain.

## Overview

This contract provides a robust counter system with:
- **Basic Operations**: increment, decrement, reset, and clear
- **Advanced Arithmetic**: multiply, divide, and conditional updates
- **Utility Functions**: even/odd checking and read-only getters
- **Error Handling**: comprehensive validation and error codes

## Features

### Core Counter Operations

| Function | Description | Returns |
|----------|-------------|---------|
| `increment` | Increases counter by 1 | Counter value |
| `increment-by` | Increases counter by specified amount | Counter value |
| `decrement` | Decreases counter by 1 | Counter value or error |
| `decrement-by` | Decreases counter by specified amount | Counter value or error |
| `reset` | Sets counter to new value | Counter value or error |
| `clear` | Resets counter to 0 | 0 |

### Conditional & Arithmetic Operations

| Function | Description | Returns |
|----------|-------------|---------|
| `set-if-greater` | Updates counter only if new value is greater | Counter value |
| `multiply-by` | Multiplies counter by factor | Counter value or error |
| `divide-by` | Divides counter by divisor | Counter value or error |
| `set-max` | Validates counter doesn't exceed max limit | Boolean or error |

### Utility Functions

| Function | Description | Returns |
|----------|-------------|---------|
| `is-even` | Checks if counter is even | Boolean |
| `is-odd` | Checks if counter is odd | Boolean |
| `get-counter` | Retrieves current counter value | Counter value |
| `get-double` | Returns counter multiplied by 2 | Calculated value |
| `get-square` | Returns counter squared | Calculated value |

## Error Codes
