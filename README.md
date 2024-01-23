# Project Setup Instructions

Follow these steps to set up the project:

1. Run `yarn` to install the project dependencies.

2. Rename the `.env.example` file to `.env`.

3. Open the `.env` file and replace `YOUR_PRIVATE_KEY_HERE` with your actual private key in hex format.

4. If you want to use the mainnet, uncomment the `MAINNET` variable in the `.env` file, otherwise it defaults to devnet.

5. Edit the `airdrop` object in the `src/config.ts` file to set up the airdrop.

6. Run by using `yarn airdrop` in the terminal.

After you've completed these steps, you should be able to run the project. If you encounter any issues, please check if you've followed all the steps correctly.
