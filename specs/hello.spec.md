# Hello World Specification

## Purpose

A trivial spec to validate that ambient-backed hyperloop sessions work end to end.

## Requirements

### Requirement: Hello World Script

The repository SHALL contain a file `hello.py` that prints "Hello from Ambient!" to stdout when executed with `python hello.py`.

#### Scenario: Run hello.py

- GIVEN the file hello.py exists in the repo root
- WHEN `python hello.py` is executed
- THEN the output is exactly "Hello from Ambient!"
