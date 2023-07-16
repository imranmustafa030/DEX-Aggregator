# DEX Aggregator

Welcome to the DEX Aggregator repository! This cutting-edge decentralized exchange (DEX) aggregator is designed and developed to provide a seamless and efficient platform for buying and selling various coins and tokens. It leverages the power of popular tools and technologies such as 1inch, Moralis Web3 API, Wagmi, React.js, and Node.js. The primary goal of this project is to ensure minimal gas fees and enhance the overall trading experience for users.

## Features

- **1inch Integration**: The DEX aggregator utilizes the 1inch protocol for swapping currencies. This integration allows users to access a wide range of liquidity sources and ensures the best possible rates for their trades.

- **Moralis Web3 API**: Moralis Web3 API is used to retrieve the current prices of different currencies. This enables users to make informed decisions while buying or selling coins and tokens.

- **Wagmi Wallet Integration**: The DEX aggregator integrates with the Wagmi wallet to provide a seamless connection between the user's wallet and the platform. This ensures secure transactions and a smooth user experience.

- **Efficient Trading**: The platform aims to optimize gas fees and provide a cost-effective trading experience. By aggregating liquidity from various DEXs and leveraging smart routing algorithms, the DEX aggregator ensures efficient and cost-efficient trades.

- **React.js and Node.js**: The frontend of the DEX aggregator is built using React.js, a popular JavaScript library for building user interfaces. The backend is developed using Node.js, a powerful JavaScript runtime. These technologies enable fast and scalable development, ensuring a robust platform.

## Installation

To set up the DEX aggregator locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/imranmustafa030/DEX-Aggregator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd dex-aggregator
   ```

3. Install the dependencies for both the frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. Configure the environment variables:

   - Create a `.env` file in the `frontend` directory and add the following variables:
     ```
     REACT_APP_1INCH_API_KEY=your_1inch_api_key
     REACT_APP_MORALIS_API_KEY=your_moralis_api_key
     REACT_APP_MORALIS_SERVER_URL=your_moralis_server_url
     ```

   - Create a `.env` file in the `backend` directory and add the following variables:
     ```
     MORALIS_APP_ID=your_moralis_app_id
     MORALIS_API_KEY=your_moralis_api_key
     ```

5. Start the frontend and backend servers:

   - In the `frontend` directory, run:
     ```bash
     npm start
     ```

   - In the `backend` directory, run:
     ```bash
     npm start
     ```

6. Access the DEX aggregator in your web browser at `http://localhost:3000`.

## Contribution

Contributions to the DEX aggregator project are welcome! If you want to contribute, please follow these guidelines:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your modifications and commit your changes.

4. Push your branch to your forked repository.

5. Create a pull request to the `main` branch of the main repository.

Please ensure that your code adheres to the project's coding style and includes appropriate tests.

We appreciate your interest and hope you find this DEX aggregator valuable for your trading needs!
