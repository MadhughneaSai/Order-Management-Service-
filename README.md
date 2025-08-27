# Order Management Service

A comprehensive gRPC-based order management service built with C++ that demonstrates microservice architecture patterns and real-world gRPC implementation.

## Overview

This project implements a production-ready order management service using gRPC and Protocol Buffers. It showcases modern C++ development practices, microservice architecture patterns, and advanced gRPC features including streaming capabilities.

The service provides comprehensive order operations including creation, retrieval, updates, listing with pagination, and real-time order status streaming.

## Features

- **Complete CRUD Operations**: Create, read, update, and list orders
- **Real-time Streaming**: Server-side streaming for order status updates
- **Pagination Support**: Efficient handling of large order datasets
- **Interceptors**: Logging middleware for request monitoring
- **Thread Safety**: Mutex-protected shared data structures
- **Graceful Shutdown**: Signal handling for clean server termination
- **Mock Data**: Pre-populated sample orders for testing
- **Client Implementation**: Example C++ client for service interaction
- **Protocol Buffers**: Strongly-typed message definitions

