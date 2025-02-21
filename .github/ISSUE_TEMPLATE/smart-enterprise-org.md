# AI Web3 Project

This project integrates various AI models and utilizes Web3 technologies for decentralized data storage, smart contracts, and blockchain-based authentication.

## Project Structure

```
ai-web3-project/
├── contracts/
│   ├── AIModelRegistry.sol
│   └── Authentication.sol
├── models/
│   ├── model1.py
│   ├── model2.py
│   └── model3.py
├── web3/
│   ├── deploy_contracts.js
│   ├── interact_with_contracts.js
│   └── web3_config.js
├── app/
│   ├── main.py
│   └── ai_manager.py
├── requirements.txt
└── README.md
```

## Setup

1. Install dependencies:
    ```sh
    pip install -r requirements.txt
    npm install web3
    ```

2. Deploy smart contracts:
    ```sh
    node web3/deploy_contracts.js
    ```

3. Run the application:
    ```sh
    python app/main.py
    ```

## Usage

Use the `/predict` endpoint to get predictions from the AI models. Example request:
```sh
curl -X POST http://localhost:5000/predict -H "Content-Type: application/json" -d '{"data": [1, 2, 3], "model_name": "model1"}'
```
