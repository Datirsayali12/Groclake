# Groclake Colabs

Welcome to the **Groclake Colabs Repository**, a collection of interactive notebooks demonstrating the features and components of the Groclake framework — a modular, extensible solution for building intelligent agents, managing data workflows, and integrating with services like MySQL, Elasticsearch, and more.

---

## Colabs Overview

### 1. **GrocAgent - Simple Chat Agent**

**What is GrocAgent?**

`GrocAgent` is a powerful and extensible Python base class tailored for creating agents in a Flask-based application. It simplifies:
- Intent handling
- Payload management
- Integration with external services

By subclassing `GrocAgent`, developers can define custom agent behaviors for:
- Chatbots  
- Recommendation engines  
- Data processors  

**Notebook Use Case:**  
Builds a simple chat agent using GrocAgent to demonstrate handling dynamic user inputs with intent-based responses.

---

### 2. **DatalakeConnection - Data Pipeline Framework**

**What is Datalake?**

The `DatalakeConnection` class extends the core `Datalake` framework to manage:
- Database connections (MySQL, Elasticsearch, Redis)
- Data pipelines for ingestion, transformation, and execution
- Secure configuration using environment variables

**Key Features:**
- Inherit and extend Datalake methods
- Configure multiple data sources
- Create modular pipelines
- Execute connections concurrently using threading
- Store and reuse connections dynamically

**Notebook Walkthrough:**
- Shows how to inherit from `Datalake`
- Step-by-step connection setup
- Pipeline creation and execution example

---

### 3. **Master File - Central Function Library**

The **Master notebook** acts as a centralized utility hub by importing and utilizing all the core components of the `groclake` library:
- `modellake`
- `resumelake`
- `datalake`
- Other related utilities

**Notebook Purpose:**
- Demonstrates payload management
- Showcases how different modules work together
- Useful for testing and debugging Groclake functionalities in one place

---

### 4. **OrderAgent - Order Status Assistant**

**What is OrderAgent?**

`OrderAgent` is a real-time conversational agent built using `GrocAgent`, designed to track customer orders.

**Features:**
-  Live order tracking
-  Estimated delivery updates
-  Multi-language support

**Example:**
- A user starts with “¿Dónde está mi pedido?” and switches to “Can I expedite the delivery?”  
- The agent handles both languages and provides seamless, relevant updates.

**Notebook Use Case:**  
Shows implementation of multilingual support and real-time status updates using the OrderAgent.

---

## Technologies Used

- Python
- Flask (backend framework)
- Elasticsearch
- MySQL
- Redis
- Google Colab
- Threading
- Environment Variables (.env)
- JSON-based payloads

---

## Getting Started

1. Clone this repository or open each notebook in Google Colab.
2. Set up environment variables (`.env`) or use Google Colab secrets.
3. Run cells sequentially and follow inline instructions.

---

## Contributing

Feel free to fork the repository and create pull requests with enhancements, bug fixes, or additional Colabs.

---


## Contact

For any questions or collaborations:  
**datirsayali12@gmail.com**  
GitHub: [https://github.com/Datirsayali12](https://github.com/Datirsayali12)

