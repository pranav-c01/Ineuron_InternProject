# Mushroom Predictor: Poisonous or Not? 🍄

The Mushroom Predictor is a sophisticated machine learning web application designed to predict mushroom edibility based on user-provided characteristics. By integrating advanced MLOps frameworks such as DVC, MLflow, and Docker, our application offers a seamless and efficient experience for users and developers alike, facilitating accurate predictions, transparent model management, and effortless deployment.

## Features 🚀

- **Accurate Predictions:** Utilize a user-friendly web interface to submit mushroom attributes and receive immediate predictions on their edibility (Poisonous or Not Poisonous).
- **MLOps Excellence:** Incorporates DVC for data management, MLflow for model tracking, and Docker for consistent deployment environments, ensuring a robust and scalable application infrastructure.
- **Dual-Port Functionality:** 
  - **Flask Application (Port 3000):** A simple, intuitive interface for submitting data and receiving predictions.
  - **Model Management Interface (Port 5000):** Detailed insights into the lifecycle of models, including active, staging, and production phases.

## Getting Started

Before you begin, ensure Docker is installed on your system to use Docker Compose for running the application. Follow Docker's official [installation guide](https://docs.docker.com/get-docker/).

### Installation

1. **Clone the Repository:**
git clone https://github.com/pranav-c01/Ineuron_InternProject.git

2. **Launch the Application with Docker Compose:**
docker-compose up

After successful execution, the web interfaces for predictions and model management will be accessible on ports 3000 and 5000, respectively.

## Usage Guide

### Making Predictions

- Navigate to `http://localhost:3000`.
- Input the mushroom's attributes as prompted.
- Submit the form to receive a prediction: `Poisonous ('p')` or `Not Poisonous ('e')`.

### Viewing Model Insights

Access `http://localhost:5000` for detailed analytics on the trained models, including performance metrics, current status, and version control.

## Built With

- **DVC (Data Version Control):** Streamlines data sharing and versioning.
- **MLflow:** Manages the ML lifecycle, including experimentation, reproducibility, and deployment.
- **Docker:** Ensures application consistency across different environments.
- **Flask:** Powers the web interface, offering a straightforward platform for user interactions.

## Contributing

We welcome contributions to enhance the Mushroom Predictor's functionality and user experience. Please review the contribution guidelines before submitting your pull requests.

## License

Distributed under the MIT License. See `LICENSE` for more information.