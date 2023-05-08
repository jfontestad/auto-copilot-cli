# Auto Copilot CLI
![logo](https://user-images.githubusercontent.com/70219513/236394679-7b1f4ac4-4454-4e91-97ea-41326d1df5b4.png)

[![npm](https://img.shields.io/npm/v/auto-copilot-cli)](https://www.npmjs.com/package/auto-copilot-cli) 
[![Node.js Package](https://github.com/rsaryev/auto-copilot-cli/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/rsaryev/auto-copilot-cli/actions/workflows/npm-publish.yml) 
[![MIT License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/transitive-bullshit/chatgpt-api/blob/main/license)
[![auto-copilot-cli npm downloads](https://img.shields.io/npm/dt/auto-copilot-cli)](https://www.npmjs.com/package/auto-copilot-cli)

![redis](https://user-images.githubusercontent.com/70219513/236693833-46c44c8b-b504-4f64-b377-78b32f4d3c26.gif)


## Description

Auto Copilot is a powerful and useful tool for developers that uses OpenAI models to translate natural language into commands, scripts, and file operations that will help you achieve your goal as safely as possible.

## Installation

```bash
npm install -g auto-copilot-cli
```

Install Script:

```bash
curl -s https://raw.githubusercontent.com/rsaryev/auto-copilot-cli/main/deployment/deploy.bash | bash
```


### Requirements

- Node.js v18.16.0 or higher - [Install Node.js](https://nodejs.org/en/download/)
- OpenAI API key - [Get OpenAI API key](https://beta.openai.com/)

### Options
- ```-h, --help``` - display help for command
- ```-V, --version``` - output the version number

### Configuration
- ```-m, --model <modelName>``` - OpenAI model name (default: "gpt-3.5-turbo")
- ```-k, --openai-api-key <key>``` - OpenAI API key ([Get OpenAI API key](https://beta.openai.com/))
- ```-e, --editor <editor>``` - Editor to open files (default: "code")

### Demo

https://user-images.githubusercontent.com/70219513/236678014-0a4ad864-3c1f-4a08-a8c9-95aaea4c9031.mov


## Usage

```bash
# Rename all files in the current directory to lowercase
$ copilot rename files in the current directory to lowercase

# Convert all images in the current directory to size 100x100
$ copilot convert all images in the current directory to size 100x100

# Create a file with implementation of binary search
$ copilot create a file with implementation of binary search

# Create a simple web server in Node.js using Koajs
$ copilot create a simple web server in Node.js using Koajs

# Start PostgreSQL in Docker
$ copilot start PostgreSQL in Docker
```
