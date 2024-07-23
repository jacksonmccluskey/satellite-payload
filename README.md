# satellite-payload

This project provides a framework for efficient bi-directional communication between a satellite device and a server application. It allows for the definition of sensor data elements within payloads, optimizing bit usage based on desired accuracy, and dynamic configuration of data parsing on the device side.

### Features

- Universal Algorithm: Define new sensors with their data types (uint, int, float, string) and desired accuracy for transmission and parsing.

- Dynamic Schema Generation: The server automatically generates an optimized schema based on defined elements, minimizing payload size.

- Bi-directional Parsing: Parse received payloads on the server and generate optimized payloads for transmission to the device.

### Device Configuration (Future): 

Implement a mechanism to send commands to the device, allowing dynamic changes in data parsing behavior based on desired accuracy.

### Benefits

- Reduced Transmission Costs: Optimized payloads minimize the number of bits required for data transmission, leading to lower bandwidth usage and potentially reduced costs.

- Improved Efficiency: Streamlined communication with the device ensures timely data collection while minimizing bandwidth usage.

- Flexibility: Easily adapt to different sensors and data requirements by defining new elements and adjusting their accuracy.
