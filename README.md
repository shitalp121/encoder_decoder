# encoder_decoder
The encode function transforms Python data structures into a byte format for efficient storage or transmission and The decode function reverses the process, converting bytes back to the original Python data structure.
Overview

This project implements an encoder and decoder system for serializing and deserializing Python data types into a compact byte format. The system supports data types such as None, integers, bytes, strings, lists, and dictionaries.

Features

Encoding: Converts Python data structures into bytes for efficient storage and transfer.

Decoding: Reconstructs original data from the byte format.

Error Handling: Robust checks for unsupported data types and malformed byte streams.

Scalable: Handles nested structures and large datasets.

