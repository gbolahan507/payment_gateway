# payment_gateway

payment-app/
│
├── flutter_app/           # Flutter frontend (mobile app)
│   ├── lib/               # Dart source code
│   ├── pubspec.yaml       # Dependencies
│   └── ...                
│
├── backend/               # Golang backend service
│   ├── main.go            # Entry point
│   ├── routes/            # API routes
│   ├── services/          # Business logic
│   ├── models/            # Database models
│   └── go.mod             
│
├── docker-compose.yml     # Multi-service container setup
├── README.md              # Documentation
└── docs/                  # API docs, diagrams, etc.
