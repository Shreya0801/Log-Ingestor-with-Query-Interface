# Ouality Log Control

This project is a simple log management system built with Node.js and Express. It consists of two main components:

1. *Log Ingestor*: A server that receives log data from various sources (APIs) and writes them to designated log files.
2. *Query Interface*: A server that provides an interface for querying logs based on different criteria such as log level, log string, timestamp, and source.

## Installation

1. Clone this repository to your local machine:

    
    git clone https://github.com/yourusername/log-management-system.git
    

2. Navigate to the project directory:

    
    cd log-management-system
    

3. Install dependencies for both components:

    
    npm install
    

## Usage

### Log Ingestor

Start the Log Ingestor server:


The Log Ingestor server will be running on port 3000 by default.

### Query Interface

Start the Query Interface server:


The Query Interface server will be running on port 4000 by default.

## Endpoints

### Log Ingestor

- POST /api/log/:logName: Receives log data from different sources and writes them to log files. Replace :logName with the name of the log file you want to write to (e.g., log1, log2, log3).

### Query Interface

- GET /api/logs: Allows querying logs based on various criteria such as level, log string, timestamp, and source. Query parameters can be used to filter logs.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
