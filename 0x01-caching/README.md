# Caching System

This project implements a basic caching system in Python, providing different caching strategies and demonstrating their usage through a series of classes.

## Overview

A caching system is designed to store frequently accessed data in a manner that allows for fast retrieval. This project explores various caching strategies, starting with a basic implementation and potentially expanding to more complex strategies like FIFO, LIFO, LRU, MRU, and LFU.

## Files

- **base_caching.py**: Contains the `BaseCaching` class, which serves as the base for all caching strategies. It defines common attributes and methods used across different caching strategies.

- **basic_cache.py**: Implements the `BasicCache` class, which inherits from `BaseCaching`. It provides a simple caching system without a capacity limit, allowing storage of key-value pairs and basic get/set operations.

- **0-main.py**: A sample script demonstrating the usage of `BasicCache`. It showcases how to instantiate the cache, add items (`put` operation), retrieve items (`get` operation), and print the current cache state.

## Requirements

- Python 3.7 or higher
- pycodestyle 2.5 (for code style adherence)
- Ubuntu 18.04 LTS (or compatible environment)

## Usage

To run the `0-main.py` script and see the basic caching system in action, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/your_repository.git

Navigate into the project directory
cd 0x01-caching

Run the main script:
./0-main.py

This script will demonstrate adding items to the cache (put operation) and retrieving items from the cache (get operation).

Notes
Each caching strategy may have specific characteristics and behaviors. While BasicCache does not impose a capacity limit, other caching strategies like FIFO, LIFO, LRU, MRU, and LFU will introduce more complex eviction policies and behaviors.

The BaseCaching class provides a foundational structure that subclasses (like BasicCache) can build upon to implement specific caching behaviors.

This project adheres to Python coding standards (pycodestyle) and includes documentation for all classes and methods as per the provided requirements.

Feel free to explore and extend this project with additional caching strategies or optimizations as needed!


This README.md file provides an overview of the project, lists the main files and their purpose, outlines usage instructions, and offers additional notes for developers who may wish to extend or modify the caching system. Adjust any details or expand upon specific caching strategies as your project evolves.

Author :2012Inga
