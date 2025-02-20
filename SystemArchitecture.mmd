graph TD;
    A[API Gateway] -->|Routes Requests| B[Cart Service];
    A --> C[Order Management Service];
    A --> D[Product Catalog Service];
    A --> E[Payment Service];
    A --> F[Notification Service];
    
    B -->|Uses| G[MongoDB];
    C -->|Uses| H[MySQL];
    D -->|Uses| I[Elasticsearch];
    E -->|Sends Events| J[Kafka Message Broker];
    F -->|Emails| K[Amazon SES];

    subgraph Load Balancers
        L[ELB]
    end
    L --> A;

    subgraph Caching
        M[Redis]
    end
    M --> B;

    subgraph Databases
        H;
        G;
    end

    subgraph Message Broker
        J;
    end

    J -->|Publishes| C;
    J -->|Subscribes| E;
