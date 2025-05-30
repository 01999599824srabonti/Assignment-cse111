Simple C++ Banking System

This is a simple object-oriented banking system written in C++. It supports account creation, login with PIN, deposit/withdrawal, fixed deposit (FDR), and monthly savings plans (DPS). User data is stored in a file (accounts.txt) for persistence.

Features

Create bank accounts with a 4-digit PIN
Secure login using masked PIN input
Deposit and withdraw money
Open Fixed Deposit Receipt (FDR) with 10% interest
Open Deposit Pension Scheme (DPS) with 6% interest
Display account details
Persistent data storage using file I/O
Requirements

C++ compiler (e.g., g++, MSVC)
Windows (for _getch() input masking)
You can replace _getch() with platform-independent alternatives for portability
accounts.txt will be created automatically if it doesn't exist
How to Compile Use your preferred C++ compiler. For example, with g++: g++ -o BankSystem main.cpp Run the executable: ./BankSystem
