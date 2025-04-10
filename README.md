# 🦉 OWL x WhatsApp MCP Server Integration

Welcome to the **OWL x WhatsApp MCP Server** project! This application seamlessly integrates the [WhatsApp MCP server](https://github.com/lharries/whatsapp-mcp) with the [OWL multi-agent framework](https://github.com/camel-ai/owl), enabling AI agents to interact with your WhatsApp data through a user-friendly Streamlit interface.

---

## ✨ Features

- **🤖 Multi-Agent Collaboration**: Leverages CAMEL-AI and OWL frameworks for dynamic agent interactions and task automation.
- **📱 WhatsApp Integration**: Access and search your personal WhatsApp messages, including media files.
- **📤 Message Dispatch**: Send messages to individuals or groups directly through the app.
- **🔍 Real-Time Information Retrieval**: Utilize web search capabilities for up-to-date information.
- **🌐 Streamlit Interface**: Provides an intuitive UI for seamless user interaction.

---

## 🛠️ How It Works

1. **Agent Roles**: Defined using CAMEL-AI's `RolePlaying` class to simulate user and assistant interactions.
2. **Toolkits Integration**: Incorporates MCPToolkit for WhatsApp data access and SearchToolkit for web searches.
3. **Task Execution**: OWL framework orchestrates the agents to perform tasks based on user input.
4. **User Interface**: Streamlit app captures user tasks and displays results in real-time.

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Bipul70701/WhatsApp_MCP_Server.git
   cd WhatsApp_MCP_Server
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Configure Environment Variables**:
   - Rename `.env_template` to `.env`.
   - Fill in the required API keys and configurations.
     
6. **Configure MCP Server**:
   - **Install and Set Up WhatsApp MCP Server**:
     - Follow the instructions in the [WhatsApp MCP server repository](https://github.com/lharries/whatsapp-mcp) to install and run the server.
     - Ensure the server is running and accessible.

6. **Run the Streamlit App**:
   ```bash
   streamlit run project.py
   ```

---

## 📂 Project Structure

```
owl-whatsapp-mcp/
├── project.py                # Main Streamlit application
├── owl/                      # OWL framework and utilities
│   └── utils/                # Utility functions and helpers
├── mcp_servers_config.json   # Configuration for MCP servers
├── requirements.txt          # List of dependencies
├── .env_template             # Example environment variables file
└── README.md                 # Project documentation
```

---

## 🔧 Key Components

- **CAMEL-AI**: Framework for designing and managing autonomous agents.
- **OWL**: Optimized Workforce Learning for real-time task management and collaboration.
- **MCPToolkit**: Facilitates interaction with WhatsApp data.
- **SearchToolkit**: Enables web search capabilities.
- **Streamlit**: Provides an interactive web interface for user interaction.

---

## 🙌 Credits

- [CAMEL-AI](https://github.com/camel-ai/camel): For the multi-agent framework.
- [OWL](https://github.com/camel-ai/owl): For real-time task management and collaboration.
- [WhatsApp MCP Server](https://github.com/lharries/whatsapp-mcp): For WhatsApp data integration.
- [Streamlit](https://streamlit.io/): For the interactive UI.

---

Made with ❤️ by Bipul Kumar Sharma
