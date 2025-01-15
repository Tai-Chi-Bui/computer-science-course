# Week 0: Binary and How Computers Work

## Overview
This week provides an introduction to the fundamental concepts of binary and how computers operate. Understanding these basics is crucial for grasping more complex topics in computer science.

## Key Concepts
- Bits and binary representation
- Data encoding systems (ASCII and Unicode)
- Basic computer architecture
- How computers process and store data

## Bits and Binary Representation

### What is a Bit?
A bit is the most basic unit of data in computing and digital communications. It can have a value of either 0 or 1. Bits are the building blocks of binary code, which is used to represent data in computers.

### Binary System
The binary system is a base-2 numeral system that uses two symbols: 0 and 1. Each digit in a binary number is referred to as a bit. Binary is the language of computers because it aligns with the digital nature of electronic circuits, which can be in one of two states: on or off.

### How Binary Works
- **Binary Counting**: Similar to the decimal system, binary numbers increase in value from right to left. Each position represents a power of 2, starting with 2^0 on the right.
  - Example: The binary number `1011` is calculated as:
    - \(1 \times 2^3 + 0 \times 2^2 + 1 \times 2^1 + 1 \times 2^0 = 8 + 0 + 2 + 1 = 11\) in decimal.

## Data Encoding Systems

### ASCII (American Standard Code for Information Interchange)
- **Basic Encoding**: ASCII uses 7 bits to represent 128 characters, including:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z) 
  - Numbers (0-9)
  - Punctuation marks and control characters
- **Extended ASCII**: Uses 8 bits (1 byte) to represent 256 characters
- **Limitations**: Cannot represent characters from non-English alphabets and most symbols

### Unicode
- **Universal Encoding**: Designed to encode characters from all writing systems worldwide
- **Multiple Encodings**:
  - UTF-8: Variable-width encoding (1-4 bytes per character)
    - Backwards compatible with ASCII
    - Most common encoding for web and software
  - UTF-16: Uses 2 or 4 bytes per character
  - UTF-32: Uses 4 bytes per character
- **Capacity**: 
  - Can represent over 140,000 characters
  - Supports modern and historical scripts
  - Includes emojis, mathematical symbols, and other special characters
- **Code Points**: Characters are assigned unique numbers called code points
  - Example: 'A' is U+0041 (same as ASCII)
  - Example: '€' (Euro sign) is U+20AC

## Basic Computer Architecture

### Components of a Computer
- **CPU (Central Processing Unit)**: The brain of the computer, responsible for executing instructions and performing calculations.
- **GPU (Graphics Processing Unit)**: Specialized processor designed to handle graphics rendering, video processing, and parallel computations.
- **Memory (RAM)**: Temporary storage used by the CPU to store data and instructions that are actively being used.
- **Storage**: Permanent storage for data and programs (e.g., hard drives, SSDs).
- **Motherboard**: The main circuit board that connects and enables communication between all computer components.
- **Power Supply Unit (PSU)**: Provides and regulates electrical power to all computer components.
- **Input/Output Devices**: Interfaces for interacting with the computer (e.g., keyboard, mouse, monitor, speakers).
- **Network Interface Card (NIC)**: Enables connection to networks and the internet, either through ethernet or wireless.
- **Cooling System**: Fans, heatsinks, and other components that prevent the computer from overheating.

### How Computers Process Data
- **Fetch-Decode-Execute Cycle**: The process by which the CPU retrieves an instruction from memory, decodes it to determine the action required, and then executes it.
- **Data Storage**: Data is stored in binary form, using bits and bytes to represent information.

## Units of Binary Data
- **Bit**: The smallest unit of data, representing a single binary value (0 or 1).
- **Byte**: Consists of 8 bits. It is the standard unit of data used to represent a character, such as a letter or number.
- **Kilobyte (KB)**: Approximately 1,024 bytes.
- **Megabyte (MB)**: Approximately 1,024 kilobytes.
- **Gigabyte (GB)**: Approximately 1,024 megabytes.
- **Terabyte (TB)**: Approximately 1,024 gigabytes.

## Importance of Bits
- **Efficiency**: Binary representation is efficient for computers to process and store data.
- **Error Detection**: Bits are used in error detection and correction algorithms, ensuring data integrity during transmission and storage.

## Resources
- [Introduction to Binary](https://www.tutorialspoint.com/computer_fundamentals/computer_binary_system.htm)
- [How Computers Work](https://www.howstuffworks.com/computer.htm)

## Exercises
- Convert decimal numbers to binary and vice versa.
- Explore how different data types are represented in binary. 