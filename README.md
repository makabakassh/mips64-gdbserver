# MIPS64 Big-Endian gdbserver Build

This repository builds a static MIPS64 big-endian gdbserver binary using GitHub Actions.

## Usage

1. Push to main branch or manually trigger workflow
2. Check Actions tab for build status
3. Download the compiled `gdbserver-mips64-be` binary from artifacts

## Binary Details

- Architecture: MIPS64 (big-endian)
- Compilation: Static (no external dependencies)
- GDB Version: 14.1
- Target: mips64-linux-gnu
