# DVD Shop API

This is a Rails API backend for a DVD shop. It supports a React frontend application and provides client-server communication for managing movies.

## Getting Started

These instructions will help you set up the project and run it on your local machine.

### Prerequisites

Make sure you have the following software installed on your machine:

- Ruby (version 3.0.2)
- Rails (version 7.0.5)

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/patrickwide/dvd-shop.git
   ```

2. Navigate to the project directory:

   ```shell
   cd dvd-shop
   ```

3. Install the dependencies:

   ```shell
   bundle install
   ```

4. Set up the database:

   ```shell
   rails db:create
   rails db:migrate
   ```

5. Seed the database with sample data:

   ```shell
   rails db:seed
   ```

### Usage

To start the server, run the following command:

```shell
rails s
```

The API will be accessible at `http://localhost:3000`.

#### Endpoints

- `GET /movies` - Retrieve a list of movies.

