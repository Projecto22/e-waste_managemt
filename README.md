# e-waste-management-using-blockchain
Ethereum Blockchain based E-Waste Management System

## Installing / Getting started

0. Clone the repo:

    ```shell
    git clone [https://github.com/siddheshhadkar/e-waste-management-using-blockchain](https://github.com/Projecto22/e-waste_managemt.git)
    cd e-waste-management-using-blockchain
    ```
    
1. Install the Truffle toolkit globally and install project dependencies:

    ```shell
    npm install -g truffle && npm install
    ```

2. In a separate shell, launch the truffle development console and then compile the contracts:

    ```shell
    truffle develop
    ```
    ```shell
    truffle compile
    ```

3. Inside the Truffle console, run the command:

    This will effectively reset your local blockchain, meaning that all existing transactions will be deleted.

    ```shell
    migrate --reset
    ```

4. Back in a first shell, start the server using:

    ```shell
    npm run dev
    ```

    A browser window should then open automatically at `http://localhost:3000`. The application homepage will open in this window. To run this application we will need to install both the metamask legacy web3 extension along with the metamask extension. (Both are available on the google extension store).

5.  Once it is installed, open Metamask and use "Import Account" to create an account from a private key. Copy the first private key from the first lines of output generated by the command `truffle develop` and paste it into the "Private Key" field.

6.  Now we need to connect to the private network we are running on our system. The private network should be running on localhost:8545 by default, so select that from the dropdown networks menu on the right corner of the metamask dialog box.

7. Also the account won't connect automatically to our application. So navigate to the browser tab in which the application is open and then navigate to connected sites in metamask and select manually connect account to site. This will allow us to use our account on the site to create accounts.

8.Everything should be good to go!


