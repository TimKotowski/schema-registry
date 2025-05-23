# schema-registry
A lightweight staging registry to manage, validate, and store Protobuf, Avro, and gRPC schemas before
publishing schemas to Buf Schema Registry (BSR)

## Structure
```plaintext
.
└── proto3/         # (Protobuf, gRPC) schemas 
    ├── stream/     # Protobuf schemas for real-time data streaming (Kafka)
    └── service/   # Protobuf schemas for service-to-service gRPC communication
```
