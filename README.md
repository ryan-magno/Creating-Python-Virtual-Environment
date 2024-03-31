# Python Virtual Environment Setup

This guide will walk you through the process of setting up a Python virtual environment and installing packages from a requirements.txt file.

## Prerequisites

- Python 3.x installed on your system

## Step 1: Create a Virtual Environment

1. Open a terminal or command prompt.
2. Navigate to the project directory using the `cd` command.
3. Run the following command to create a virtual environment:

    ```shell
    python -m venv venv
    ```

    This will create a new directory named `venv` which will contain the virtual environment.

4. Activate the virtual environment:

    - On Windows:

      ```shell
      venv\Scripts\activate
      ```

    - On macOS/Linux:

      ```shell
      source venv/bin/activate
      ```

    You should see `(venv)` in your command prompt, indicating that the virtual environment is active.

## Step 2: Install Packages from requirements.txt

1. Make sure you are in the project directory and the virtual environment is active.
2. Run the following command to install the packages listed in the requirements.txt file:

    ```shell
    pip install -r requirements.txt
    ```

    This will install all the required packages and their dependencies.

3. You're all set! You can now start working with your Python project within the virtual environment.

## Additional Notes

- To deactivate the virtual environment, simply run the following command:

  ```shell
  deactivate
  ```

- It's a good practice to include the `venv` directory in your project's `.gitignore` file to avoid committing it to version control.

- Remember to update the requirements.txt file whenever you add or remove packages from your project.

## Conclusion

By following the steps outlined in this guide, you should now have a Python virtual environment set up and ready to use. Installing packages from a requirements.txt file ensures that your project's dependencies are consistent across different environments.