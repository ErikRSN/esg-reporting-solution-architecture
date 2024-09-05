# Application Architecture

This repository contains the PlantUML diagram representing the architecture of the application.

## Diagram

The following diagram illustrates the relationships between different microservices and libraries in the application:

![Architecture Diagram](architecture_of_the_app.png)

## Components

- **ESGDataMicroservice**: This microservice handles ESG data.
- **ESGAnalyticsLib**: A library used for ESG analytics.
- **NotificationMicroservice**: This microservice handles notifications.
- **CommonUtilities**: A set of common utilities used across the application.

## Usage

To view or edit the PlantUML diagram, open the `graph.puml` file in Visual Studio Code with the PlantUML extension installed.

To export the diagram as a PNG file, follow these steps:

1. Open the command palette (`Ctrl+Shift+P`).
2. Type `PlantUML: Export Current Diagram` and select it.
3. Choose the PNG format.
4. Specify the output location and save the file as `architecture_of_the_app.png`.
