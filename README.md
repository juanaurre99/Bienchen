# Bienchen

.
├── docker-compose.yml        # Docker Compose file to define and run your application and its dependencies
├── app/                      # Application code and configuration
│   ├── api/                  # API server code and configuration
│   │   ├── Dockerfile        # Dockerfile for the API server
│   │   ├── main.py           # Main application code for the API server
│   │   └── requirements.txt # Python dependencies for the API server
│   ├── influxdb/             # InfluxDB configuration and scripts
│   │   ├── Dockerfile        # Dockerfile for InfluxDB
│   │   └── influxdb.conf     # InfluxDB configuration file
│   └── config/               # Configuration files for the application
│       └── config.py         # Configuration for the API server
├── data/                     # Directory for storing data
├── docs/                     # Project documentation
├── tests/                    # Test code and data
└── README.md                # Project documentation and setup instructions
