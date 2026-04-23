# Order Network eXchange Standard (onX)

## Universal Fulfillment System for the AI Era

The Order Network eXchange Standard (onX), provides a standardized interface between AI agents and fulfillment systems through the Model Context Protocol (MCP).

This standard enables AI assistants like Claude to seamlessly interact with any fulfillment system, streamlining commerce operations from order capture through delivery.

## Project Purpose

- **Standardize Fulfillment Integration**: Define a universal protocol for fulfillment operations
- **Enable AI-Driven Commerce**: Allow AI agents to manage orders, inventory, and fulfillment
- **Simplify Implementation**: Provide plug-and-play adapters for different Fulfillment backends
- **Accelerate Innovation**: Create a foundation for next-generation commerce automation

## Project Structure

### [/docs](./docs/README.md)

Comprehensive documentation covering:

- Order Network eXchange specification and standards
- Architecture and design decisions
- Integration guides for different stakeholders
- API reference and examples

### [/schemas](./schemas)

JSON Schema definitions for:

- Order data structures
- Customer information
- Product catalog
- Inventory models

## Core Capabilities

The server provides 12 essential fulfillment operations:

**Action Tools**

- `create-sales-order` - Create new orders from any channel
- `update-order` - Modify order details and line items
- `cancel-order` - Cancel orders with reason tracking
- `fulfill-order` - Mark orders as fulfilled and return shipment details
- `create-return` - Create returns for order items with refund/exchange tracking

**Query Tools**

- `get-orders` - Retrieve order information
- `get-customers` - Get customer details
- `get-products` - Get product information
- `get-product-variants` - Retrieve variant-level data
- `get-inventory` - Check inventory levels
- `get-fulfillments` - Track fulfillment status
- `get-returns` - Query return records and status


## Contributing

We welcome contributions from the community! Whether you're:

- A Fulfillment vendor creating an adapter
- A developer improving the core server
- A user reporting issues or suggesting features

Please open an issue or pull request to get started.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Resources

- [Commerce Operations Foundation](https://commerceopsfoundation.org/)
- [Model Context Protocol](https://modelcontextprotocol.io) - The foundation protocol
- [onX Reference Server](https://github.com/commerce-operations-foundation/mcp-reference-server)
