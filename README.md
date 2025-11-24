# Solana Address Generator

Rust-based tool for custom Solana address generation.

## Download

Check Releases section for latest executable.

## Usage

```bash
# Find address starting with prefix
solana-vanity -p MOON
-> MOONZHaFkSZQWAQqqZG5rvwM3ew3VFAXGUJXfVVw9rj4

# Start with prefix + end with suffix
solana-vanity -p MOON -s 12345
-> MOONZHaFkSZQWAQqqZG5rvwM3ew3VFAXGUJXfVV12345
