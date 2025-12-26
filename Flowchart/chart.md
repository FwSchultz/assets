flowchart LR
  Discord[Discord Server] -->|Slash Commands / Events| Bot[Discord Bot Core]

  Bot -->|HTTP/WebSocket| CRCON[HLL CRCON Tool API]
  Bot -->|HTTP| Steam[Steam Web API]

  Bot --> Adapter[API Adapter Layer]
  Adapter --> HLL[HLL API Schema]
  Adapter --> Vietnam[HLL: Vietnam Adapter (später)]

  Bot --> DB[(SQLite/Postgres)]
  Bot --> Cache[(Redis optional)]
  Bot --> Logs[Logging/Monitoring]
