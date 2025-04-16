# SmartVendorHub-App

# An Agentic AI Market App for Pre-Booking & Intelligent Services

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](YOUR_HUGGING_FACE_SPACE_URL_HERE)

## Tagline

Empowering street vendors and customers in urban India with an intelligent pre-booking and service platform.

## Overview

This project aims to address the challenges faced by street vendors and the needs of customers in urban traffic areas in India by developing an AI-powered platform. The application utilizes a multi-agent system with a Marketplace of Cognitive Programs (MCP) to provide intelligent services such as demand forecasting, quality assessment (conceptual), and market matching. Customers can pre-book items, and vendors can manage their stock and access valuable insights. The user interface is built using Gradio, and data is stored using DuckDB.

## Key Features

* **Consumer Request Submission:** Customers can submit their desired food items, quantity, unit, and required date.
* **Farmer Stock Submission:** Farmers and vendors can list their available stock, including item name, quantity, unit, quality grade, and availability date.
* **Market Matching Engine:** The application automatically matches consumer requests with available farmer stock.
* **Pre-Booking Portal:** Customers can simulate pre-booking items from listed stock.
* **Agent-Based Architecture:** The system is built using specialized AI agents for different functionalities.
* **Marketplace of Cognitive Programs (MCP):** A central registry allows agents to register, discover, and interact with each other.
* **Demand Forecasting (Simplified):** A basic agent predicts demand for specific items in locations.
* **Vendor Services:** Vendors can access services like demand forecasting through the application.
* **User-Friendly Interface:** Built with Gradio for easy interaction.
* **Data Storage:** Utilizes DuckDB for efficient data management.

## Agent-Based Architecture & MCP

This application employs a modular agent-based architecture where different functionalities are handled by specialized AI agents. These agents interact through a Marketplace of Cognitive Programs (MCP):

* **Data Management Agent:** Manages data storage and retrieval using DuckDB.
* **Consumer Agent:** Handles the submission of consumer requests.
* **Farmer Agent:** Manages the submission of farmer stock information.
* **Matching Agent:** Responsible for matching consumer demands with farmer supplies.
* **Pre-Booking Agent:** Handles the simulation of pre-booking items.
* **Demand Forecasting Agent:** (Simplified) Predicts demand for specific items.
* **Vendor Agent:** Acts as an interface for vendors to access various services like demand forecasting.

The MCP acts as a central registry where these agents can register their services and discover other agents they need to interact with to fulfill their tasks. This architecture promotes modularity, scalability, and allows for the easy addition of new intelligent services in the future.

## Getting Started

To run this application locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone YOUR_REPOSITORY_URL_HERE
    cd YOUR_REPOSITORY_NAME
    ```
2.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Gradio application:**
    ```bash
    python app.py
    ```
    This will launch the application in your web browser (usually at `http://localhost:7860`).

## Usage

The application features several tabs for different functionalities:

* **Consumer Request:** Customers can enter their requirements for food items.
* **Farmer Stock:** Farmers and vendors can list their available produce.
* **Market Matches:** Displays potential matches between consumer requests and farmer stock.
* **Pre-Booking:** Allows consumers to simulate pre-booking items.
* **Vendor Services:** Provides access to services like demand forecasting for vendors.

Simply navigate through the tabs and fill in the required information to use the application.

## Contributing

Contributions to this project are welcome! If you have any ideas for improvements, new features, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch for your changes.
3.  Make your changes and commit them.
4.  Push your changes to your fork.
5.  Submit a pull request to the main repository.

Please ensure your code follows the project's coding style and includes appropriate tests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

* This project utilizes the following open-source libraries:
    * [Gradio](https://gradio.app/)
    * [DuckDB](https://duckdb.org/)
    * [Pandas](https://pandas.pydata.org/)
* [Hugging Face](https://huggingface.co/) for providing the Spaces platform for deployment.

* ![Screenshot 2025-04-16 225410](https://github.com/user-attachments/assets/329cdac1-a039-45d5-b463-06eaef74afbc)
![Screenshot 2025-04-16 225244](https://github.com/user-attachments/assets/1ef9cf18-4753-4738-8fbe-b95ae8912a9c)
![Screenshot 2025-04-16 225209](https://github.com/user-attachments/assets/3ef1936f-cd0d-403d-b6cc-45f491e773f9)
![Screenshot 2025-04-16 225156](https://github.com/user-attachments/assets/8695cbdd-d73c-4591-ad58-1fff0d545c4a)
![Screenshot 2025-04-16 225149](https://github.com/user-attachments/assets/246e4be3-b4f3-4eb4-aba7-d7d0b0dbc740)
![Screenshot 2025-04-16 225029](https://github.com/user-attachments/assets/e52a9c5c-309e-4c4a-8ad0-a89b4caa339d)

