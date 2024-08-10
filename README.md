#README.md
## Instructions to Build and Run

### Prerequisites
- Ensure that Java Development Kit (JDK) version 11 or higher is installed.
- The project should be run on the course virtual lab machine which is pre-configured for this coursework.

### Building the Project
1. Download or clone the project to your local directory.
2. Open a terminal and navigate to the project's root directory.
3. Compile the Java files using the following command:


## Complete and Working Functionality

### Implemented Features
- **A Record Resolution:** Successfully resolves and returns the IP address for a given domain.
- **TXT Record Resolution:** Parses and returns TXT records associated with the domain.
- **CNAME Resolution:** Correctly identifies and returns the canonical name for the domain.
- **NS Record Resolution:** Parses and returns the Name Server records.
- **MX Record Resolution:** Correctly parses and returns the Mail Exchange server details.

### Known Issues or Limitations
- The program has been tested primarily with specific DNS servers. Other DNS servers may produce unexpected results.
- Error handling for non-existent domains or unsupported record types is basic and may not cover all edge cases.
- Logging and additional testing features are not fully implemented.
- there are some issues with parsing the methods for resolver.java

### Notes
- Ensure the network connection on the virtual lab machine is stable to avoid DNS query timeouts.
- If you encounter any issues, please refer to the comments within the code for troubleshooting or additional details.

