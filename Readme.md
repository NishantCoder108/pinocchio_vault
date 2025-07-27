# Pinocchio Vault

A secure vault program built using Pinocchio , allowing users to deposit and withdraw funds with proper access control using Program Derived Addresses (PDAs).

## 🚀 Features

- **Secure Deposits**: Users can safely deposit funds into their personal vault
- **Controlled Withdrawals**: Only the vault owner can withdraw funds
- **PDA-based Security**: Utilizes Program Derived Addresses for enhanced security

## 📦 Prerequisites

- Rust (latest stable version)
- Cargo (Rust's package manager)

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd pinocchio_vault
   ```

2. Build the program:
   ```bash
   cargo build-spf
   ```

## 📝 Learning Notes

### Project Setup
- Initialize project: `cargo new pinocchio_vault --lib --edition 2021`
- Add dependencies: `cargo add pinocchio pinocchio-system`
- For deployment artifacts, add to [Cargo.toml]:
  ```toml
  [lib]
  crate-type = ["lib", "cdylib"]
