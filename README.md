# Print-Relay-App
**Print Relay** is an open-source, self-hosted platform for managing and sharing printers (and potentially other devices) across networks. Designed with modern technologies, it enables seamless device management, real-time communication, and collaborative printing workflows.

**Print Relay Client App** is a cross-platform .NET MAUI application that connects to the self-hosted server to manage and execute print jobs. Designed to work seamlessly with the Print Relay backend, the client app enables users to access shared printers, view print queues, and submit jobs in real-time.


## 🚀 Features

- **Cross-Platform Compatibility**:
    
    - Available on Windows, macOS, iOS, and Android.
- **Real-Time Updates**:
    
    - Connects to the self-hosted server via SignalR for live synchronization.
    - Updates on job status and device availability.
- **Native Printing**:
    
    - Uses OS-specific APIs for executing print jobs efficiently.
- **User-Friendly Interface**:
    
    - Simplified UI for device discovery, job submission, and queue management.

---

## 🌱 Who is this for?

The **Print Relay** is designed for:

- **End Users**:
    - Seamless access to shared printers across networks.
- **Small Offices**:
    - Centralized control over shared printers without IT complexity.
- **Distributed Teams**:
    - Seamless connectivity across networks or geographic locations.
- **Educational Institutions**:
    - Manage lab and library printers efficiently.

---

## 🛠️ Architecture

- **Framework**: .NET MAUI
- **Protocol**: WebSocket (via SignalR)
- **Printing**: Native OS APIs (e.g., `PrintDocument` for Windows, `NSPrintOperation` for macOS)
- **Real-Time Communication**: SignalR

### Print Relay Server

- [Self-Host Server](https://github.com/SaintScraTchY/Print-Relay-Server)

---

## 🔄 Roadmap

### Client App

- [ ]  Develop cross-platform MAUI application.
- [ ]  Implement SignalR for real-time updates.
- [ ]  Add support for native OS printing APIs.
- [ ]  Enhance UI/UX for job and queue management.
- [ ]  Add print job history and retry functionality.
- [ ]  Support additional device types (e.g., scanners).

---

## 🤝 Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

---

## 📜 License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## 🌐 Contact

For questions, suggestions, or feedback, please contact me at [Telegram](https://t.me/SaintScraTchY).
