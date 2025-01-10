## TX Link
```bash 
https://explorer.solana.com/tx/5dziqBf2JEVWY7uDRQa6i5hYpLKNhJt1rXSKDBQVYT15bZyWjcoLxDkYBbULKqt8LBHSvcDPuvtEBEY9r252Xzqg/?cluster=devnet
```

# Prerequisites: PreReq Rust Program from Turbine3

## Overview
These prerequisites are meant to assess your ability to follow processes, execute tasks, debug
simple errors (intentionally placed), and ship code. They are not a test of your typescript or
coding skills.

- **Program Derived Addresses (PDA)**: PDAs allow us to sign transactions with a Public Key derived from a deterministic seed, providing additional security.
- **Interface Definition Language (IDL)**: The IDL is a JSON file that defines the public interface for interacting with the program. It contains account structures, instructions, and error codes for Solana programs.
---

## **Setup and Execution Instructions**

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:Stevolisis/turbin3-steven-joseph-final-project.git
    ```
    ```bash 
    cd turbin3-steven-joseph-final-project
    ```

2. **Install Repo**:
   ```bash
   cargo build
    ```

3. **Generate your wallet.json**:
   ```bash
   solana-keygen new --outfile dev-wallet.json
    ```

4. **Request SOL using you wallet public key**:
   Head to https://faucet.solana.com and request SOL

5. **Run the Enrollment Script**:
   ```bash
   yarn ts-node enroll.ts
    ```

6. **Expected Output**:
   ```bash
   Success! Check out your TX here: https://explorer.solana.com/tx/<transaction-hash>?cluster=devnet
    ```
    