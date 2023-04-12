# Assignment: Building a Blockchain Indexer with Node.js

### Overview: You have been tasked with building a blockchain indexer using Node.js, with a preference for using Nest.js as the framework and Redis queues for handling asynchronous tasks. The indexer will be responsible for processing and indexing transactions from a blockchain network, allowing users to search and retrieve transaction data efficiently.

### Acceptance Criteria:

1.  Blockchain Integration: The indexer should be able to connect to a blockchain network (EVM compatible chain) using appropriate libraries or APIs and fetch transaction data.
2.  Transaction Indexing: The indexer should process transactions from the blockchain network and index them into a database for efficient retrieval. The indexed data should include relevant transaction details such as transaction ID, sender/receiver addresses, transaction amount, and timestamp.
3.  Search and Retrieval: The indexer should provide APIs or endpoints for users to search and retrieve transaction data. Users should be able to search transactions based on transaction ID, sender/receiver addresses, transaction amount, and timestamp, and receive accurate results in a timely manner.

### Bonus Criteria (Optional):

1. Failover Handling: Implement failover mechanism to automatically switch to an alternate EVM RPC endpoint when one endpoint is unavailable.
2. Error Handling: Implement comprehensive error handling mechanisms, such as logging, to ensure robustness and reliability of the indexer.
3. Testing: Thoroughly test the indexer using automated testing frameworks (e.g., Jest, Mocha) to ensure functionality, performance, and reliability. Test cases should cover different scenarios, including positive and negative test cases, and edge cases. Bonus points for high test coverage and comprehensive testing strategies.
4. Dockerization: Create a Dockerfile to package the indexer as a Docker container, with all the necessary dependencies and configurations. The Docker container should be easy to deploy and run in any environment supporting Docker.

5. Include the dockerized application in a Docker Compose file along with other necessary services, such as Redis and MongoDB.
