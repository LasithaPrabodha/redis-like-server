# Redis-like Server

This project implements a simplified version of a Redis-like server in Go, providing basic functionalities similar to Redis.

![ezgif-1-21fadfcd2b](https://github.com/LasithaPrabodha/redis-like-server/assets/10921870/fdc5363f-5b89-44ad-896e-6010003ad618)

## Features

- Handles TCP connections and processes incoming requests.
- Supports various Redis commands including SET, GET, HSET, HGET, and HGETALL.
- Implements an Append-Only File (AOF) persistence mechanism for data durability.

## Getting Started

### Prerequisites

- Go (version 1.16 or higher) installed on your system.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/LasithaPrabodha/redis-like-server.git
   ```

2. Navigate to the project directory:

   ```bash
   cd redis-like-server
   ```

3. Build the server:

   ```bash
   go build
   ```

### Usage

1. Start the server:

   ```bash
   ./redis-like-server
   ```

2. The server will start listening on port `6379`.

3. Use a Redis client to connect to the server and execute commands.

### Supported Commands

- SET key value
- GET key
- HSET hash key value
- HGET hash key
- HGETALL hash
