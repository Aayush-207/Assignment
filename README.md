# Ticket Booking System (BookMyShow Clone)

A scalable, robust, and high-performance system for movie ticket booking, designed to handle high concurrency, database consistency, and efficient caching.

## 📁 Project Structure

```
├── assets/             # System design diagrams and media
├── docs/               # System design & architecture documentation
│   ├── ARCHITECTURE.md      # High-level architecture overview
│   ├── SCHEMA.md            # Database schema design and entity relationships
│   ├── CONCURRENCY.md       # Strategies for handling concurrent bookings and race conditions
│   ├── CACHE.md             # Caching strategy (Redis)
│   ├── QUEUE.md             # Message queue design (Kafka/RabbitMQ) for asynchronous processing
│   ├── DESIGN-DECISIONS.md  # Key engineering decisions and trade-offs
│   └── DESIGN-UPDATES.md    # Log of architecture modifications and updates
└── README.md           # Main documentation landing page
```

## 📖 Documentation Quick Links

To understand the core design and architectural decisions of this system, refer to the following documentation files:

1. **[System Architecture](docs/ARCHITECTURE.md)**: High-level overview of the components, request flow, and technologies.
2. **[Database Schema Design](docs/SCHEMA.md)**: Detailed entity-relationship models, tables, columns, constraints, and optimization strategies.
3. **[Concurrency Management](docs/CONCURRENCY.md)**: Solutions for double-booking issues, distributed locking, transaction isolation levels, and seat reservation expirations.
4. **[Caching Strategy](docs/CACHE.md)**: Details on cache integration, invalidation policies, and hot seat data.
5. **[Message Queues](docs/QUEUE.md)**: Asynchronous payment processing, email notifications, and background job scheduling.
6. **[Design Decisions](docs/DESIGN-DECISIONS.md)**: Technical rationale behind database choices, scaling strategies, and architectural trade-offs.
7. **[Design Updates](docs/DESIGN-UPDATES.md)**: Log of system modifications, evolution, and post-mortem adjustments.
