[back](../README.md)
# FAIR Digital Data Types
In the "old" ePIC Data Type Registry existed two types of data types:
- **Basic Info Types** - Basic validation with regex based on a JSON data type.
- **Info Types** - Combined data type from many (Basic) Info Types.

Since the schema of the Info Types has much in common with the schema of the Kernel Information Profiles (in this new context called "Type Profiles"), I decided to merge the two types of data types into one. 
A Data Type therefore is now just representing the functionality of a Basic Info Type.
The functionality of an Info Type is now represented by a Type Profile.
Any Type Profile can be referenced as a data type.
