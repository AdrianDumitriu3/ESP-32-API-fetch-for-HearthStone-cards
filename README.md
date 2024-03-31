# ESP-32-API-fetch-for-HearthStone-cards

Code for implementing a data fetch app for android devices using ESP32 and Bluetooth connection.

This code is for an ESP32 API data fetcher that communicates with an Android device via Bluetooth Low Energy (BLE). Here's a short description of why it's good for your project section:

Modular Design: The code is structured into classes and functions, promoting modularity and code reuse. This enhances readability and maintainability, crucial for larger projects.

Use of Libraries: It leverages popular libraries such as ArduinoJson, WiFi, HTTPClient, and BLEDevice, saving development time and ensuring reliability through well-tested code.

Error Handling: There are error checks throughout the code, ensuring that Bluetooth and Wi-Fi are enabled, and providing error messages if not. This improves robustness and user experience.

BLE Communication: It sets up a BLE server with characteristics for data listing and data details, allowing bidirectional communication between the ESP32 and Android device. This enables efficient data transfer.

Dynamic JSON Handling: The code efficiently handles JSON data from the API, both for listing and fetching details of Hearthstone minions. It uses DynamicJsonDocument to parse and manipulate JSON data.

WiFi Connection Management: It includes a class for managing WiFi connections, providing flexibility for connecting to different networks by setting SSID and password dynamically.

Clear Serial Output: The code includes helpful serial print statements for debugging and monitoring the device's behavior, such as indicating when data is sent or if there's an overflow during JSON creation.

Efficient Resource Management: It utilizes dynamic memory allocation for JSON documents, optimizing memory usage and preventing memory leaks.

Bluetooth Pairing Alert: It optionally provides a pairing alert when the ESP32 is waiting for a client connection, enhancing user experience by indicating the device's status.
