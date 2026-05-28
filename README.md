# Spreadsheet Processor

A command-line spreadsheet processor written in C that reads, stores, and evaluates table data with support for structured input parsing and robust error handling.

This project demonstrates 2D array processing, file parsing, modular C design, command-line programming, and defensive handling of invalid input cases.

## Overview

Spreadsheet Processor is a C-based command-line program that processes spreadsheet-style input files. The program reads structured table data, stores it internally, evaluates cell contents, and prints cleaned or processed spreadsheet output.

The goal of this project was to practice building a larger C program with multiple source files, structured data representation, input validation, and reliable error handling.

## Features

- Reads spreadsheet-style data from input files
- Parses structured table input
- Stores table data using organized internal data structures
- Processes and formats spreadsheet output
- Handles invalid or malformed input cases
- Uses modular source and header files
- Includes shell-based testing support
- Supports comparison against expected output files

## Tech Stack

- C
- 2D Arrays
- File I/O
- Error Handling
- Modular C Design
- Shell Scripting
- Makefile / Command-Line Build Tools

## Repository Structure

```text
Spreadsheet-Processor/
├── README.md
├── data.c
├── data.h
├── input.c
├── input.h
├── tidydata.c
├── test.sh
├── input-*.txt
└── expected-*.txt
