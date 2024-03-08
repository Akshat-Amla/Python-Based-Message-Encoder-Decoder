# Message Encode and Decode Application

## Project Description

This is a Python application that provides a graphical user interface (GUI) for encoding and decoding messages using a specified key. The application uses the Tkinter library for the GUI and incorporates base64 encoding for secure message manipulation.

## Technologies Used

- **Python 3.x:** The core programming language used for building the application.
- **Tkinter:** A standard GUI (Graphical User Interface) toolkit for Python that provides easy-to-use interfaces for desktop applications.
- **base64:** Used for secure encoding and decoding of messages.

## Libraries Used

### Tkinter

Tkinter is the standard Python interface to the Tk GUI toolkit. It is widely used for creating desktop applications with graphical interfaces.

### base64

The `base64` library provides functions to encode and decode data using the base64 encoding scheme. In this project, it ensures secure encoding of messages.

## Features

- User-friendly GUI
- Encode and decode functionality
- Secure encoding using base64 encoding
- Easy-to-understand interface for key and mode selection

## How I Built This

### GUI Design

The GUI was designed using Tkinter, taking advantage of its simplicity and ease of use. The layout includes input fields for the message and key, a mode selection field, and buttons for encoding, decoding, resetting, and exiting.

### Encoding and Decoding Logic

The encoding and decoding functions were implemented with a simple algorithm that manipulates the characters of the message based on the provided key. The use of base64 encoding ensures secure data manipulation.

### User Interaction

The application allows users to input the message, key, and select the mode (encode or decode). The result is displayed in the GUI, providing a seamless user experience.
