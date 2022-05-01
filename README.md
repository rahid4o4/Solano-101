# Solano-101
assignment to implement solano commands
Solana-Development-with-React-Anchor-Rust-and-Phantom

Installation

Install the dependencies

npm i

Note: If you get error with npm i then use "npm i --legacy-peer-deps"

Start a local Solana node
solana-test-validator

Open new terminal and Build the anchor project
anchor build

Fetch the project ID for the build:
solana address -k target/deploy/<programname>-keypair.json

Update the project ID in the Rust program located at projectname/programs/src/programname.rs with the output from above.

Run the tests
anchor test
Note: If you get error then stop the solana-test-validator and run the tests 7. Change into the app directory and install the dependencies:

cd app && npm i
Note: If you get error with npm i then use "npm i --legacy-peer-deps" 8. Run the client-side app

npm start
