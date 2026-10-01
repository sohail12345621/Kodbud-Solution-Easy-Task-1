# NOVA — Rule-Based AI Chatbot

A lightweight rule-based conversational chatbot developed in Python as part of **Task 1 of the Artificial Intelligence Internship at Kodbud Solutions**.

NOVA processes user input, evaluates predefined conversational rules, and generates an appropriate response through an interactive command-line interface.

---

## Overview

This project demonstrates the fundamental architecture of a simple rule-based chatbot.

Rather than relying on external APIs or machine-learning models, NOVA uses deterministic rules and conditional logic to identify supported user inputs and return predefined responses.

The implementation focuses on:

- Input normalization
- Rule-based response generation
- Conversational interaction
- Command handling
- Continuous execution
- Graceful termination

---

## Objectives

The primary objective is to understand how basic conversational systems can be implemented using Python.

The chatbot is designed to:

1. Accept natural-language input from the user.
2. Normalize the input for consistent rule matching.
3. Evaluate predefined conversational rules.
4. Generate an appropriate response.
5. Maintain an interactive conversation loop.
6. Terminate gracefully when an exit command is provided.

---

## Features

- Rule-based conversational engine
- Input normalization using string processing
- Greeting recognition
- Identity and capability responses
- Basic Python-related responses
- Help functionality
- Appreciation handling
- Multiple exit commands
- Fallback response for unsupported queries
- Continuous command-line interaction

---

## System Flow

```text
User Input
    │
    ▼
Input Normalization
    │
    ▼
Rule Evaluation
    │
    ├── Greeting
    ├── Identity
    ├── Capabilities
    ├── Help
    ├── Python
    ├── Appreciation
    └── Exit
    │
    ▼
Predefined Response
    │
    ▼
Display Response
    │
    ▼
Continue Conversation