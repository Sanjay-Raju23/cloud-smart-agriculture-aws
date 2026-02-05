# Cloud-based Smart Agriculture Dashboard (AWS)

## Overview
This project implements a cloud-based smart agriculture monitoring system using AWS serverless services and IoT devices. It enables real-time monitoring of soil and environmental conditions to support data-driven farming decisions.

## Architecture
- ESP32 with soil and environmental sensors
- AWS IoT Core for secure device communication
- AWS Lambda for serverless data processing
- AWS DynamoDB for scalable data storage

## Workflow
1. Sensors collect real-time data from the field.
2. ESP32 publishes data securely to AWS IoT Core.
3. AWS Lambda processes incoming messages.
4. Processed data is stored in DynamoDB.
5. Data can be visualized using a web dashboard.

## Technologies Used
- AWS IoT Core
- AWS Lambda
- AWS DynamoDB
- ESP32
- Python (MicroPython)

## Outcome
- Real-time agricultural data monitoring
- Scalable and cost-efficient cloud architecture
- Improved decision-making for smart farming

## Future Enhancements
- Weather API integration
- Automated irrigation control
- Advanced analytics and alerts

## Publication
- **IoT-Based Intelligent Dustbin for Real-Time Urban Waste Monitoring and Management**  
  Published in IEEE Xplore, 2025  
  https://ieeexplore.ieee.org/document/11254708

