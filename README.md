# Relay

Relay is an email newsletter service built while following the book **Zero to Production in Rust** by Luca Palmieri.

This application is a backend service for managing an email newsletter. Users can subscribe to the newsletter by submitting their email address through an API endpoint. The service confirms their subscription via a confirmation email and stores verified subscribers in a database. The newsletter author can then send an email broadcast to all confirmed subscribers.

The project intentionally mirrors the concerns of a production system rather than a toy app. It deals with input validation, error handling, database migrations, background email delivery, authentication, and deployment pipelines.

## Tech Stack

* Rust
* Actix Web
* Tokio
* Reqwest
* PostgreSQL (later in the project)
* SQLx (later in the project)

## Status

This project is currently under development as I progress through the chapters of *Zero to Production in Rust*. Features and implementation details will continue to evolve as more concepts are introduced.

## Running the Project

```bash
cargo run
```

The server will start on the configured local address.

## Running Tests

```bash
cargo test
```

Book: https://www.zero2prod.com/