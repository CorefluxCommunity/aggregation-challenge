### Internship Challenge: MQTT data aggregation

#### Objective:

Create service that connects to an MQTT broker, subscribes to specific topics, aggregates data from those topics, and processes it based on user-defined configurations.

Key Components:

MQTT Client. (such as: https://github.com/dotnet/MQTTnet)

Configuration: Allow the user to define configurations in a file and/or other method (JSON/YAML/Other). The configuration can include:

- MQTT broker address, port, clientId, and credentials.
- List of topics to subscribe to.
- Data aggregation strategy (e.g., averaging data from specific topics, collecting all data for a certain time window, etc.).
- Quality of Service (QoS) levels for each topic.
- Optional filters or rules for processing the data before aggregation.

Data Aggregation: Implement different aggregation strategies, like:

- Collecting and averaging numeric data from specific topics.
- Create a way of configuring recepies (trough a file, mqtt, w/e)

Service Behavior: The service can run indefinitely.

Output: Define the output method for aggregated data. It can be:
- Pushed back to an MQTT topic. 
- Stored in database (nice to have)
- Printed to the console (meh)
- etc.

#### Deliverables
1. **Source Code:** Provide the complete source code with comments and documentation explaining key parts of the code.
2. **Configuration File / or whatever you use to configure:** Include a sample configuration file with all the available options and defaults.
3. **User Guide:** A brief guide explaining how to configure the program, run it, and interpret the output.
4. **Test Cases:** Include a set of test cases or scenarios that demonstrate the program’s functionality and robustness.

#### Evaluation Criteria
- **Configurability:** The ease with which the program can be configured.
- **Code Quality:** Cleanliness, readability, and organization of the code. Proper use of comments and documentation.
- **User Experience:** Quality of the configuration interface , ease of use, and clarity of the user guide.
- **Bonus Points:** Visualization of aggregated data.

#### Submission
Please submit your solution in a GitHub repository with clear instructions on how to set up and run the program. Include any additional documentation or resources that would assist in evaluating your submission.

#### Tools and repos
Mqtt-Explorer (nice to have)
https://github.com/CorefluxCommunity/CorefluxMQTTcSharpAPI
https://github.com/dotnet/MQTTnet?tab=readme-ov-file
---

#### Broker details
Broker: iot.coreflux.cloud
Port: 1883

Good luck! We are excited to see your innovative approaches and solutions!
