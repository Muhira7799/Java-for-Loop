# Java `for` Loop Example

A minimal Java program that demonstrates how a `for` loop works by counting from 0 to 4.

## What It Demonstrates

```java
for (int i = 0; i < 5; i++) {
    System.out.println("i=" + i);
}
```

A `for` loop has three parts in its header:

| Part | Code | Meaning |
|------|------|---------|
| Initialization | `int i = 0` | Runs once before the loop starts |
| Condition | `i < 5` | Checked before every pass; the loop stops when it is false |
| Update | `i++` | Runs after every pass and increases `i` by 1 |

## How It Works

1. `i` starts at `0`.
2. While `i < 5`, the loop prints the current value of `i`.
3. After each pass, `i` increases by 1.
4. When `i` reaches `5`, the condition is false and the loop ends.

## Output

```
i=0
i=1
i=2
i=3
i=4
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### Compile

```bash
javac For_Loop.java
```

### Run

```bash
java For_Loop
```

## Try It Yourself

- Count from 1 to 10: `for (int i = 1; i <= 10; i++)`
- Count down: `for (int i = 5; i > 0; i--)`
- Count in steps of 2: `for (int i = 0; i < 10; i += 2)`

## Project Structure

```
.
├── For_Loop.java
└── README.md
```

## Next Steps

- Use a `for` loop to add up the numbers from 1 to 100
- Print a multiplication table
- Try nested `for` loops to draw patterns
- Compare with `while` and `do-while` loops

