# YOLOv5 People Counter with InfluxDB Integration

[![License](https://img.shields.io/badge/license-AGPL--3.0-blue)](https://github.com/your-username/your-repo/blob/main/LICENSE)

Real-time people counting solution using YOLOv5 object detection and InfluxDB integration. This project provides an efficient and accurate way to count people in images and videos, with the ability to store and analyze the data in InfluxDB.

## Features

- Real-time people counting using YOLOv5 object detection
- Seamless integration with InfluxDB for storing and querying person count data
- High accuracy and efficiency for diverse environments and scenarios

## License

This project is licensed under the [AGPL-3.0 License](https://github.com/your-username/your-repo/blob/main/LICENSE). Please review the license file for more details.

## Getting Started

To get started with the YOLOv5 People Counter, follow the instructions below:

1. Clone the repository:

   ```bash
   git clone https://github.com/DianaChica/InfluxDB-People-Counter.git

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt

3. Configure the InfluxDB connection in the database.py file:
    ```bash
    # Replace with your InfluxDB credentials
    url = "your_url"
    token = "your_token"
    org = "your_org"
    db = "your_db"

4. Run the people counting script:
    ```bash
    python count_people.py

## Acknowledgments
This project utilizes the YOLOv5 object detection framework developed by Ultralytics. Special thanks to their team for their valuable contribution.


