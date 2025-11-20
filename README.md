# Faculty Cabin Management System

A simple Python console application to manage faculty names and their assigned cabin locations. The program supports user lookups and secure owner updates (add/delete) of records.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data Structure](#data-structure)
- [Usage](#usage)
- [Installation](#installation)

---

## Overview

This project implements a command-line interface that allows two types of users:

- **User:** Search for faculty members by name (or part of the name) to find their cabin number.
- **Owner:** Log in with credentials to add new faculty records or delete existing ones.

The data is stored in a Python dictionary for quick lookups and updates.

---

## Features

- Case-insensitive partial search for faculty names.
- Secure owner login with username/password.
- Add new faculty with confirmation.
- Delete faculty by exact name match.
- Repeated operations until explicit exit.
- Simple and intuitive interaction flow.

---

## Data Structure

Uses a Python dictionary:

a = {
"dr. baseera a": "G-01",
"dr. vinod bhatt": "G-02",
...
"Dr Prashant GK": "A-250"
}


Faculty names are keys and cabin numbers are values.

---

## Usage

1. Run the script: `python faculty_cabin_management.py` (or copy-paste the code in your environment)
2. Choose user type (user=1/owner=2).
3. For user:
   - Enter faculty name or partial name to search.
   - View matching results or "Data not available".
4. For owner:
   - Enter username and password.
   - Choose to add (1) or delete (2) a faculty record.
   - Follow prompts to complete operations.
5. Exit when done.

---

## Installation

No external dependencies. Requires Python 3.x installed.

Simply clone/download and run the script.

---
