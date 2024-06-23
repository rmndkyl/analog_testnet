## ANALOG_TESTNET
Follow this tutorial to Complete GMP gateway contract on Sepolia and Shibuya


## Send a message using a GMP gateway contract on Sepolia Testnet (Daily)

**Access Remix here**:
https://remix.ethereum.org/

1. Create a file named `BranchlessMath.sol` and copy the script from BranchlessMath.sol on [GitHub](https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/utils/BranchlessMath.sol), then paste it into the file.

2. Create a file named `Primitives.sol` and copy the script from Primitives.sol on [GitHub](https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/Primitives.sol), then paste it into the file.

3. Create a file named `IGateway.sol` and copy the script from IGateway.sol on [GitHub](https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/interfaces/IGateway.sol), then paste it into the file.

4. Copy the path of the `BranchlessMath.sol` file by right-clicking on the file name and selecting "Copy path." Then paste this path into `Primitives.sol` in the import statement: `import { BranchlessMath } from "paste the path here";`

5. Copy the path of the `Primitives.sol` file by right-clicking on the file name and selecting "Copy path." Then paste this path into `IGateway.sol` in the import statement: `import { GmpSender } from "paste the path here";`

6. Select the `IGateway.sol` file and go to the "Solidity Compiler" menu. Click "Compile IGateway.sol."

7. Go to the "Deploy & Run Transactions" menu.

8. In the "Environment" dropdown, select "Injected Provider - Metamask" (Change your Metamask network to Sepolia Testnet).

9. In the "Contract" dropdown, select `IGateway - contract/IGateway.sol`.

10. Copy the Gateway Address: Sepolia Testnet `0x000000007f56768de3133034fa730a909003a165`.

11. Paste the Gateway Address into the "At Address" field, then click the "At Address" button.

12. Check the details under the "Deployed/Unpinned Contracts" section. Click the details of the `submitMessage` function and fill in the following details:
    1. destinationAddress: Enter the address of the contract created on Sepolia.
    2. destinationNetwork: `7`
    3. executionGasLimit: `30000`
    4. data: `0x01`

14. Click "transact," confirm the pop-up in your wallet, and wait for the transaction to succeed.

15. Check the terminal in Remix, copy the transaction hash, and verify it on [Sepolia Blockscout](https://eth-sepolia.blockscout.com/).

16. Submit the transaction hash to [Analog Testnet](https://testnet.analog.one/#/?signup&referral=MCFIAH).

*Verification on Analog may be delayed. If you encounter an error, wait 30 minutes and try verifying again.

## Send a message using a GMP gateway contract on Shibuya Testnet (Daily)

**Access Remix here**:
https://remix.ethereum.org/

1. Create a file named `BranchlessMath.sol` and copy the script from BranchlessMath.sol on [GitHub](https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/utils/BranchlessMath.sol), then paste it into the file.

2. Create a file named `Primitives.sol` and copy the script from Primitives.sol on [GitHub](https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/Primitives.sol), then paste it into the file.

3. Create a file named `IGateway.sol` and copy the script from IGateway.sol on [GitHub](https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/interfaces/IGateway.sol), then paste it into the file.

4. Copy the path of the `BranchlessMath.sol` file by right-clicking on the file name and selecting "Copy path." Then paste this path into `Primitives.sol` in the import statement: `import { BranchlessMath } from "paste the path here";`

5. Copy the path of the `Primitives.sol` file by right-clicking on the file name and selecting "Copy path." Then paste this path into `IGateway.sol` in the import statement: `import { GmpSender } from "paste the path here";`

6. Select the `IGateway.sol` file and go to the "Solidity Compiler" menu. Click "Compile IGateway.sol."

7. Go to the "Deploy & Run Transactions" menu.

8. In the "Environment" dropdown, select "Injected Provider - Metamask" (Change your Metamask network to Shibuya Testnet).

9. In the "Contract" dropdown, select `IGateway - contract/IGateway.sol`.

10. Copy the Gateway Address: Shibuya Testnet `0x000000007f56768de3133034fa730a909003a165`.

11. Paste the Gateway Address into the "At Address" field, then click the "At Address" button.

12. Check the details under the "Deployed/Unpinned Contracts" section. Click the details of the `submitMessage` function and fill in the following details:
    1. destinationAddress: Enter the address of the contract created on Shibuya.
    2. destinationNetwork: `5`
    3. executionGasLimit: `30000`
    4. data: `0x01`

13. Click "transact," confirm the pop-up in your wallet, and wait for the transaction to succeed.

14. Check the terminal in Remix, copy the transaction hash, and verify it on [Shibuya Blockscout](https://shibuya.blockscout.com/).

15. Submit the transaction hash to [Analog Testnet](https://testnet.analog.one/#/?signup&referral=MCFIAH).

*Verification on Analog may be delayed. If you encounter an error, wait 30 minutes and try verifying again.

## THANKS TO
[HAPPY CUAN](https://t.me/HappyCuanAirdrop) FOR MAKE THIS TUTORIALS POSSIBLE!
