# Customer Churn Prediction Application

This application is designed to predict customer churn using machine learning techniques, Then it will summerize the information using an LLM, and then generates an email to be sent to the user based on the information we have. Follow the instructions below to set up and run the application.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Python 3.10](https://www.python.org/downloads/)
- [Homebrew](https://brew.sh/) (for macOS users)
- [Poetry](https://python-poetry.org/docs/#installation) (for dependency management)

## Installation

1. **Clone the Repository**:

   Open your terminal and clone the repository:

   ```bash
   git clone https://github.com/amanabiy/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. **Install Python 3.10** (if not already installed):

   If you don't have Python 3.10 installed, you can install it using Homebrew:

   ```bash
   brew install python@3.10
   ```

3. **Create a Virtual Environment**:

   Create a virtual environment using Python 3.10:

   ```bash
   python3.10 -m venv venv
   ```

4. **Activate the Virtual Environment**:

   Activate the virtual environment:

   ```bash
   source venv/bin/activate
   ```

5. **Install Poetry** (inside the virtual environment):

   You can install Poetry using the following command:

   ```bash
   curl -sSL https://install.python-poetry.org | python3 -
   ```

6. **Add Poetry to PATH**:

   To ensure that the Poetry command is recognized, add the following line to your shell configuration file (e.g., `~/.bashrc`, `~/.bash_profile`, or `~/.zshrc`):

   ```bash
   export PATH="$HOME/.local/bin:$PATH"
   ```

   After adding this line, run the following command to apply the changes:

   ```bash
   source ~/.zshrc  # or source ~/.bashrc, depending on your shell
   ```

7. **Install Dependencies**:

   Use Poetry to install the required dependencies:

   ```bash
   poetry install
   ```

8. **Set Up Environment Variables**:

   Copy the `.env.sample` file to create your `.env` file:

   ```bash
   cp .env.sample .env
   ```

   Make sure to fill in the necessary environment variables in the `.env` file before running the application.

## Usage

1. **Run the Application**:

   After installing the dependencies, you can run the application. Depending on how your application is structured, you might have a main script. For example:

   ```bash
   streamlit run main.py
   ```

2. **Access the Application**:

   If your application is a web application, open your web browser and navigate to `http://localhost:8501`

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.


## Acknowledgement

This is the first project in the Headstarters Accelerator program, follow [this link](https://headstarter.co/) to learn more about Headstarter.