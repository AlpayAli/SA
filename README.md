# KdG MineralFlow
 Developed collaboratively by Alpay and Ilian.

**Efficient and Seamless Logistics for Mineral Distribution**

KdG MineralFlow is a logistics management system developed for Krystal Distributie Groep (KdG), specializing in the distribution of essential raw materials such as gypsum, iron ore, cement, petcoke, and slag. The system modernizes KdG's logistics operations, enabling adaptability, seamless integration, and efficient material flow from arrival planning to storage.

## Features

### Material Management
KdG MineralFlow supports the following materials with detailed tracking and pricing systems:
- **Gypsum**:
  - A soft sulfate mineral used in construction, agriculture, and cement production.
  - Storage cost: $1/ton/day
  - Sale price: $13/ton
- **Iron Ore**:
  - A key material for steel production, commonly hematite and magnetite.
  - Storage cost: $5/ton/day
  - Sale price: $110/ton
- **Cement**:
  - A critical binding agent used in construction for concrete and mortar.
  - Storage cost: $3/ton/day
  - Sale price: $95/ton
- **Petcoke**:
  - A high-carbon material used as fuel in energy generation and industrial processes.
  - Storage cost: $10/ton/day
  - Sale price: $210/ton
- **Slag**:
  - A byproduct of metal smelting used in construction and cement production.
  - Storage cost: $7/ton/day
  - Sale price: $160/ton

### Vendor Operations
- **Delivery Management**:
  - Handles up to 40 trucks/hour, with a capacity of 1 kiloton/hour.
- **Storage Capacity**:
  - Warehouses support up to 500 kt each, with overflow up to 110% capacity (550 kt).
- **Inventory Management**:
  - Tracks available storage space, preventing overcapacity issues.

### Buyer Operations
- **Order Integration**:
  - Seamless integration with purchase orders to manage shipping logistics.
- **Commission-Based Pricing**:
  - A 1% commission is charged for every successful shipment.

### Logistics Efficiency
- Optimized material flow from delivery to storage and shipping.
- Scalable design adaptable to new material types and system requirements.

## Project Structure

The project is organized into the following key modules:
- **Land**: Manages transportation and logistics for material deliveries via road.
- **Warehouse**: Handles inventory management, storage capacities, and overflow tracking.
- **Water**: Oversees shipping logistics, including ship loading and scheduling.
- **Mineral**: Tracks and manages raw material details, including pricing and descriptions.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AlpayAli/SA.git
   cd SA
   docker-compose up
   ```
