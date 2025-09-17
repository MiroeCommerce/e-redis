# Redis Docker Stack

This repository contains the necessary configuration to run a Redis database and the RedisInsight GUI using Docker Compose.

## How to Run

1.  Clone this repository.
2.  Create a `.env` file from the example or by copying the content from the README. Set your desired `REDIS_PASSWORD`.
3.  Run the command: `docker-compose up -d`
4.  You can now connect to Redis at `localhost:6379`.
5.  Access the RedisInsight GUI by navigating to [http://localhost:5540](http://localhost:5540) in your browser.

## Services

* **Redis:** The database, running on port `6379`.
* **RedisInsight:** The GUI, accessible on port `5540`.
