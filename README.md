## Description
A simple bank application designed to optimize requests handling.

## Scope
App is designed to handle requests from multiple clients. Each client can have multiple accounts. Each account can have multiple transactions in different currencies.

## Design
Combines *memory based persistence (fast)* to maximize availability, and *Event Sourcing* pattern to ensure data consistency.

## Installation
```
  yarn
```

## Usage

```
  yarn start
  yarn test
```

