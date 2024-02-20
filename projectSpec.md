# Log File Analyzer Project Specification

## Objective

Develop a Perl script capable of reading, parsing, and analyzing log files from web servers, applications, or any systems that generate text logs. The script will extract specific information, generate summaries, and identify patterns or potential issues within the log files.

## Features

### 1. Read a Log File

- Implement functionality to read a log file line by line.
- Allow users to specify the log file path as a command-line argument.

### 2. Extract Information

- Parse each line to extract vital information such as timestamps, log levels (INFO, ERROR, DEBUG, etc.), and messages.
- Adjust parsing logic based on the log file format in use.

### 3. Filter Logs

- Filter logs by different criteria, such as log level or date range.
- Utilize Perl's regular expressions and text processing capabilities for filtering.

### 4. Summarize Data

- Generate summaries from the logs, like the count of error messages, list of unique warnings, or frequency of specific events.

### 5. Search for Patterns

- Allow users to search for specific patterns or keywords in the logs.
- Highlight the importance of regular expressions for this feature.

### 6. Report Generation

- Output a report based on the log analysis.
- Support simple text reports, either printed to the console or saved to a file.

## Learning Outcomes

- **File Handling**: Learn to open, read, and write files in Perl.
- **Regular Expressions**: Gain proficiency in Perl's regular expression support for text processing.
- **Data Structures**: Utilize Perl's arrays and hashes for data storage and manipulation.
- **Subroutines**: Develop reusable code blocks for specific tasks, enhancing code modularity and readability.

## Getting Started

- **Installation**: Ensure Perl is installed on your system (`perl -v`).
- **Log File**: Choose a sample log file to work with, such as an Apache access log or any system log file.

## Additional Challenges

- Develop modular parsing strategies to handle different log file formats.
- Implement a simple user interface for easier interaction with your script, considering command-line options or a basic web interface using frameworks like Dancer2 or Mojolicious.
