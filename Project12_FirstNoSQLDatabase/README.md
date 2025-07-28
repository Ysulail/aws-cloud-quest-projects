# Project12 First No SQL Database

## 📌 Project Overview
In this project, I built a scalable NoSQL solution using **Amazon DynamoDB** to help a streaming service store and manage customer viewing data. The main goal was to support features like digital bookmarks and collect metadata from a wide range of devices—all without needing a strict schema. This solution enhanced user experience by tracking where users left off and which devices they used.

## 🚀 Key Features & Services
 **Amazon DynamoDB Table**: Created a table named `UserVideoHistory` to store user-specific data.
- **NoSQL Flexibility**: Stored items with attributes like:
  - `userId`
  - `lastDateWatched`
  - `lastStopTime`
  - `preferredLanguage`
  - `rating`
  - `supportedDeviceTypes`
- **Scalability & Speed**: DynamoDB provides low-latency reads/writes and handles large-scale metadata seamlessly.

## 🖥️ Application in Action
![DynamoDB Table](p12-1.png)

## 📊 Lessons Learned
- Amazon DynamoDB allowed flexible data modeling without needing to define a fixed schema.
- Adding user-specific metadata like device types and stop times was seamless and scalable.
- NoSQL solutions are ideal for applications where the data structure evolves frequently or varies by record.
