# Deploying a Verifier Contract on a Testnet


This project is part of the Metacrafters Poly Proof Advanced Course, Module 3. 
&nbsp;

In this project, we have to build a circuit using `circom`, compile a `Verifier Contract` and deploy it to the `Mumbai Testnet`

&nbsp;

### Circuit Diagram
&nbsp;
![Circuit Diagram](https://authoring.metacrafters.io/assets/cms/Assessment_b05f6ed658.png?updated_at=2023-02-24T00:00:37.278Z)

&nbsp;


### Project Setup

- Clone the repository
- Install the dependencies
    ```
    npm i
    ```
- Create a .env file to store wallet private key
    ```
    WALLET_PRIVATE_KEY= #YOUR_PRIVATE_KEY
    ```

### Circuit Compilation and Deployment

- Compile the circuit
    ```
    npx hardhat circom
    ```
- Deploy the verifier Contract
    ```
    npx hardhat run scripts/deploy.ts --network mumbai
    ```
    &nbsp;
The script will compile the contract and deploy it onto the Mumbai Testnet. The address of the contract will be printed on the console. 


