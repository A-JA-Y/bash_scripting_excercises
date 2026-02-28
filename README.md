# Bash Scripting Exercises

This small collection of shell scripts lives in the root of the
repository and demonstrates basic Bash constructs (variables, loops,
conditionals, user input, etc.).  
Each script is executable (`#!/bin/bash` at the top) and can be run
directly from the command line once the execute bit is set.

## Scripts

- **`questionnaire.sh`** – simple interactive questionnaire that asks for
  your name, location and favourite coding website, then repeats the
  answers.
- **`fortune.sh`** – “fortune‑teller” that prompts for a yes/no question
  and replies with a random canned response.
- **`countdown.sh`** – counts down to zero from the integer given as the
  first argument.
- **`bingo.sh`** – generates a random bingo ball number (B‑O) and prints
  it.
- **`five.sh`** – orchestrates the other four programs in sequence.

## Usage

1. Make sure the files are executable:

   ```sh
   chmod +x *.sh
   ```

2. Run any script directly:

   ```sh
   ./questionnaire.sh
   ./countdown.sh 5        # counts down from 5
   ./bingo.sh
   ./fortune.sh
   ```

3. Or run `five.sh` to execute all four in order:

   ```sh
   ./five.sh
   ```

## Notes

- `countdown.sh` expects a positive integer argument; otherwise it prints
  `false`.
- `fortune.sh` loops until you enter a question ending in `?`.
- All scripts are POSIX‑compliant Bash and should work on any
  Unix‑like system with Bash installed.

Feel free to inspect and modify the code – the comments in each file
explain the core logic.

```# Bash Scripting Exercises

This small collection of shell scripts lives in the root of the
repository and demonstrates basic Bash constructs (variables, loops,
conditionals, user input, etc.).  
Each script is executable (`#!/bin/bash` at the top) and can be run
directly from the command line once the execute bit is set.

## Scripts

- **`questionnaire.sh`** – simple interactive questionnaire that asks for
  your name, location and favourite coding website, then repeats the
  answers.
- **`fortune.sh`** – “fortune‑teller” that prompts for a yes/no question
  and replies with a random canned response.
- **`countdown.sh`** – counts down to zero from the integer given as the
  first argument.
- **`bingo.sh`** – generates a random bingo ball number (B‑O) and prints
  it.
- **`five.sh`** – orchestrates the other four programs in sequence.

## Usage

1. Make sure the files are executable:

   ```sh
   chmod +x *.sh
   ```

2. Run any script directly:

   ```sh
   ./questionnaire.sh
   ./countdown.sh 5        # counts down from 5
   ./bingo.sh
   ./fortune.sh
   ```

3. Or run `five.sh` to execute all four in order:

   ```sh
   ./five.sh
   ```

## Notes

- `countdown.sh` expects a positive integer argument; otherwise it prints
  `false`.
- `fortune.sh` loops until you enter a question ending in `?`.
- All scripts are POSIX‑compliant Bash and should work on any
  Unix‑like system with Bash installed.

Feel free to inspect and modify the code – the comments in each file
explain the core logic.
