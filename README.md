# CDE-cURL-Deployment
How to collect the JSON payload used for cURL-based deployment

## Background
Cloudera's Public Cloud Data Platform is designed for flexibility. Users may create a variety of configuration options to meet their needs. While many configuration options are available via the user interface, there are even more configuration options available using available APIs. Using APIs for deploying services is useful for different scenarios, including:
* Deploying and managing CDE Services via code
* Applying configurations which are not available via the UI
* Create a template for standard or iterative configurations

This is one example to create a CDE service cURL command by harvesting the needed information from your browser's developer console. For this examplem, Chrome was used. Most browsers offer a developer console, and typically it may be accessed using the F12 key, or under a **Tools** or **More Tools** menu option.
