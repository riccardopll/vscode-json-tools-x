# JSON Tools X

[![CI](https://github.com/riccardopll/vscode-json-tools-x/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/riccardopll/vscode-json-tools-x/actions/workflows/ci.yml)

JSON Tools X is a VS Code extension for fast JSON editing in-place.

## Install

- VS Code Marketplace: [riccardopll.rpll-json-tools](https://marketplace.visualstudio.com/items?itemName=riccardopll.rpll-json-tools)
- Open VSX: [riccardopll/rpll-json-tools](https://open-vsx.org/extension/riccardopll/rpll-json-tools)

## Usage

1. Open a JSON/JSONC file.
2. Select the JSON you want to transform (or select nothing to target the whole file).
3. Run one of the commands from the Command Palette.

## Commands

| Command Palette Title | Command ID               | What it does                                   |
| --------------------- | ------------------------ | ---------------------------------------------- |
| `JSON: Minify`        | `json-tools.minify`      | Converts JSON/JSONC to compact JSON            |
| `JSON: Stringify`     | `json-tools.stringify`   | Converts JSON into an escaped JSON string      |
| `JSON: Deserialize`   | `json-tools.deserialize` | Converts a stringified JSON value back to JSON |
