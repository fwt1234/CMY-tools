# CMY Encoding/Decoding Tool

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![HTML5](https://img.shields.io/badge/HTML5-Compatible-green.svg)

Two JavaScript-based tools for encoding/decoding CMY values in PNG images and converting to/from binary data.

## Features

### 🔧 Tool 1: Extract CMY data and binary data from PNG
| Window | Input | Output | Description |
|--------|-------|--------|-------------|
| 1 | Base64 data | PNG image | Decodes Base64 string to PNG |
| 2 | PNG image | CMY data | Extracts CMY values from pixels (requires width/height settings) |
| 3 | CMY data | Binary data | Encodes for RB-TMB decoder |
| 4 | Binary data | CMY data | Decodes binary back to CMY values |
| 5 | CMY data | PNG image | Renders CMY data as PNG |

### 🔍 Tool 2: Save binary data derived RB-TMB pixels as PNG
| Window | Input | Output | Description |
|--------|-------|--------|-------------|
| 1 | Binary data (RB-TMB) | CMY data | Decodes with width/height settings |
| 2 | CMY data | PNG image | Renders CMY values as PNG |
| 3 | PNG image | Base64 data | Converts PNG to Base64 string |
| 4 | Base64 data | PNG image | Decodes Base64 to PNG |

## 🚀 Usage
1. Clone this repository, run in HTML or JavaScript
