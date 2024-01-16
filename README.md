# Network Configuration for Motorcar Routing

This repository contains the XML configuration files for an advanced motorcar routing network, designed to be versatile and comprehensive, with special adaptations for ferry routes and terminals.

## Features

- **Robust Road Network Support**: Accommodates a wide range of road types including motorways, residential streets, service roads, tracks, and pedestrian paths.
- **Ferry Route Integration**: Includes ferry routes as a separate edge type, with ferry speed set to 20 km/h.
- **Ferry Terminal Functionality**: Implements ferry terminals with specialized connectivity and waiting time considerations.
- **Enhanced Speed Settings**: Detailed speed settings based on road type, surface, and smoothness, reflecting realistic travel conditions.
- **Barrier Management**: Configurations for various types of barriers, contributing to accurate drive time calculations.
- **Flexible Height Restrictions**: Handles vehicle height restrictions for roads and ferry routes.

## Installation

To use this configuration:
1. Clone the repository to your local machine.
2. Integrate the XML files into your GIS or routing software according to its specific data import procedures.

## Usage

These configuration files are designed to be used with GIS software or routing applications that support custom XML configurations. Adjust the settings in the XML files as needed to match your specific use case.

## Contributing

Contributions to this project are welcome. Please submit pull requests with your proposed changes for review.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Walker, for initial modifications including track inclusion and adjusted speed values.
- Ivo Teruggi, for further enhancements including ferry route and terminal integration.
