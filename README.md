# ddb

<!-- ABOUT THE PROJECT -->
## About The Project

SQL Server Express in Docker with a volume to persist data.

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Docker


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/he3/ddb.git
   ```
2. Create a sapassword.env file with a password for the sa account
   ```js
   SA_PASSWORD=Password_1
   ```
3. Create and run the container (from the ddb directory)
   ```sh
   docker-compose up -d
   ```
   
### When you are done
4. Stop the container and clean up. The data volume will still exist for the next time you run docker-compose up
   ```sh
   docker-compose down
   ```
