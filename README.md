# LogWatch

## Project Purpose
LogWatch is a log monitoring microservice skeleton built with standard Java. It provides a clean foundation for ingesting log files, analyzing entries, and generating reports.

## Architecture Overview
- `model/`: Data structures for log entries and reports.
- `service/`: Core services for reading logs, analyzing data, and producing reports.
- `config/`: Application configuration definitions.
- `Main`: Entry point for wiring components together.

## How to Run
1. Compile the sources:
   ```bash
   javac src/Main.java src/config/AppConfig.java src/model/LogEntry.java src/model/LogReport.java src/service/LogFileReader.java src/service/LogAnalyzer.java src/service/ReportGenerator.java
   ```
2. Run the application:
   ```bash
   java -cp src Main
   ```

> Note: This is a skeleton project. Implementation details will be added later.
