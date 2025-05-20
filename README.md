# Miller-Rabin Primality Test

This is a Python implementation of the **Miller-Rabin primality test**, a probabilistic algorithm used to determine whether a number is prime.

## 🧪 About

The Miller-Rabin test is much faster than basic trial division and is especially useful for testing very large numbers. It doesn't guarantee absolute certainty but gives high confidence after multiple rounds of testing.

## 📌 How It Works

- The input number `n` is tested for primality.
- The algorithm performs `k` rounds (default is 5) to check if `n` passes the test.
- Each round picks a random base and checks conditions based on modular exponentiation.
- If `n` passes all rounds, it is probably prime.
- If it fails any round, it is definitely not prime.

## 🚀 How to Run

1. Clone the repository or copy the script.
2. Run the Python file:


