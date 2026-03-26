# crypto-duth
Companion repository containing **Jupyter Notebooks** for the course "Cryptography" at the Democritus University of Thrace.

All notebooks are located in the `notebooks/` directory.

## Structure
```text
.
├── notebooks/
│   ├── 01.Caesar.ipynb
│   ├── 02.BlockCiphers.ipynb
│   └── 03.MathBackground.ipynb
│   └── 04.RSA-Diffie-Hellman.ipynb
└── README.md
```

## Notebooks
- `01.Caesar.ipynb`: Introduction to the Caesar cipher, a simple substitution cipher.
- `02.BlockCiphers.ipynb`: Overview of block ciphers, including AES.
- `03.MathBackground.ipynb`: Mathematical foundations for cryptography, including modular arithmetic, modular inverse, Euler's totient function, the Extended Euclidean Algorithm and the Chinese Remainder Theorem.
- `04.RSA-Diffie-Hellman.ipynb`: Implementation of RSA and Diffie-Hellman key exchange algorithms.
- `05.Hash-Functions.ipynb`: Introduction to hash functions and their applications in cryptography.

## Running the Notebooks
You can run the notebooks either locally or using a cloud-based Jupyter environment.

### Local Setup
This repository uses the **uv** package manager.

1. Install `uv` if you haven't already:
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
   
2. Install dependencies:
   ```bash
    uv sync
    ```
   
You can use any package manager of your choice, but make sure to install the required dependencies listed in `pyproject.toml`.

### Cloud-Based Jupyter Environment
You can also run the notebooks in a cloud-based Jupyter environment such as Google Colab. Simply upload the notebooks to your environment and ensure you have the necessary dependencies installed.

## Requirements
- `pycryptodome`: A self-contained Python package of low-level cryptographic primitives.
- `cryptography`: A package which provides cryptographic recipes and primitives.

## Educational Use
This repository is intended for educational purposes and is part of the curriculum for the "Cryptography" course at the Democritus University of Thrace. The notebooks are designed to provide hands-on experience with cryptographic concepts and algorithms.

## License
This repository is licensed under the MIT License. See `LICENSE` for details.