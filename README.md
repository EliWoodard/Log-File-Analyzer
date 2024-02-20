# Log File Analyzer

## Overview

The Log File Analyzer is a Perl script designed to read, parse, and analyze log files from various sources such as web servers, applications, or systems. It extracts crucial information, filters logs based on specific criteria, generates summaries, identifies patterns, and produces reports to help understand the log files' content better.

## Features

- **Log Reading**: Reads log files line by line, allowing for detailed analysis.
- **Information Extraction**: Parses logs to extract timestamps, log levels, and messages.
- **Log Filtering**: Filters logs by criteria like log level or date range.
- **Data Summarization**: Summarizes log data to highlight error counts, unique warnings, and event frequencies.
- **Pattern Searching**: Searches for specific patterns or keywords within the logs.
- **Report Generation**: Generates reports based on analysis, which can be outputted to the console or saved to a file.

## Requirements 

- VSCode 1.86.2
- Windows 10
- Perl 5 or later installed on your machine. To verify Perl installation, run `perl -v` in your command line.

## Installation

1. Clone the repository or download the project files.
2. Ensure Perl is correctly installed on your system.

## Usage

To use the Log File Analyzer, follow these steps:

```shell
perl log_analyzer.pl <path_to_log_file>