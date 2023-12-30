# Transport-Sustainable
The "Transport Sustainable" dataset captures various aspects of transportation-related events and activities with a focus on sustainability. The dataset includes information from different data sources, such as traffic camera data, GPS data, and sensor data, providing a comprehensive view of transportation-related incidents and trends.

The dataset is organized with the following fields:

Device ID: Unique identifier associated with the data source or device contributing to the dataset.

Data type: Categorization of the type of data collected, including traffic camera data, GPS data, and sensor data.

Timestamp: Date and time when the data was recorded, providing a temporal reference for each observation.

Location: Geographic coordinates (latitude, longitude) indicating the specific location associated with the recorded data.

Value: Information or measurement associated with the transportation event, such as the reason for a bridge closure, traffic violation details, or passenger count.

Trust: A numerical value representing the reliability or confidence level of the recorded data, ranging from 0 to 1. Higher values indicate greater trustworthiness.

Output: Binary indicator (0 or 1) representing specific outcomes or conditions related to sustainability or transportation events. For example, a value of 1 might indicate an event or condition that aligns with sustainable practices.

Example Entries:

Device ID: 1234567890

Data type: Traffic camera data
Timestamp: 10/26/2023 0:25
Location: 37.7833,-122.4167
Value: Bridge closure due to construction
Trust: 0.8
Output: 1
Device ID: 1234567891

Data type: GPS data
Timestamp: 10/26/2023 17:28
Location: 37.7833,-122.4167
Value: Black car running red light
Trust: 0
Output: 0
Device ID: 1234567892

Data type: Sensor data
Timestamp: 10/26/2023 15:13
Location: 37.7833,-122.4167
Value: Bridge closure due to construction
Trust: 0.4
Output: 0
Device ID: 1234567893

Data type: GPS data
Timestamp: 10/26/2023 3:15
Location: 37.7833,-122.4167
Value: Bridge closure due to construction
Trust: 0.5
Output: 1
Device ID: 1234567894

Data type: GPS data
Timestamp: 10/26/2023 9:28
Location: 37.7833,-122.4167
Value: 188 passengers
Trust: 0
Output: 0

This dataset provides valuable insights into sustainable transportation practices, traffic incidents, and other relevant information that can be leveraged for analysis, planning, and decision-making in the transportation domain.





