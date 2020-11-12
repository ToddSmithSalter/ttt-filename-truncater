# Todd's Tiny Tools — Filename Truncater

A tiny CLI tool to truncate filenames to an input number of characters.

## Installation

Not yet published to npm. Clone this directory and run the following to test from the repo directory:

```bash
npm install
npm link
```

## How it works

This tool walks the directory and it's subfolders from where the tool is run. Each filename is parsed and truncated to an input number of characters. If no value is passed in, files will be truncated to 32 characters and the extension will be appended.

```bash
$ ttt-filename-truncator
```

The above command will truncate all filenames to 32 characters plus the extension length.

```bash
$ ttt-filename-truncator 48
```

The above command will truncate all filenames to 48 characters plus the extension length.
