# Steps to Install Yarn on Windows

## Step 1: Install Node.js
1. Download and install Node.js from the [official website](https://nodejs.org/).

## Step 2: Enable Corepack
1. Open PowerShell or Command Prompt.
2. Run the following command to enable Corepack, which includes Yarn:
    ```sh
    corepack enable
    ```

## Step 3: Verify Yarn Installation
1. Run the following command to check if Yarn is installed correctly:
    ```sh
    yarn --version
    ```

If you encounter an error related to running remote scripts in PowerShell, follow these commands:

## Step 4: Set Execution Policy in PowerShell (if needed)
1. Run steps 4 & 5, if you find the yarn version is obsolete.
2. Open PowerShell as Administrator.
3. Run the following command to allow remote scripts to run:
    ```sh
    Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    ```
4. Confirm the change by typing `Y` and pressing `Enter`.

## Step 5: Update Yarn
1. In the PowerShell run this command to update yarn:
    ```sh
    yarn set version stable
    ```

You should now have Yarn installed and ready to use.
