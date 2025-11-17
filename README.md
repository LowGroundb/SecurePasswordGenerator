# SecurePasswordGenerator

A small Python tool that generates secure, random passwords. Includes a simple "waiting" animation while generating.

## Features
- Generates strong passwords using Python's `secrets` module
- Configurable length and character sets (letters, digits, symbols)
- Copy/paste friendly output

## Requirements
- Python 3.8+

## Run
```bash
# If the entry point is main.py
python3 main.py

# Or if the script is named after the project
python3 secure_password_generator.py
```

## Example
```text
Length: 20
Include symbols: yes
Password: tD9Y$wqN@rj7VbK!4sL%
```

## Ideas / Next steps
- CLI flags (e.g. `--length`, `--no-symbols`, `--no-ambiguous`)
- Entropy estimate and strength hints
- Option to output multiple passwords at once
- Copy-to-clipboard option
