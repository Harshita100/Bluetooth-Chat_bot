# Bluetooth Communication System

## 📱 Real-time Bluetooth Information Exchange System

A serverless communication system enabling seamless information sharing between server and client devices through Bluetooth technology. Perfect for environments with limited or no internet connectivity.

## 🔌 Socket Communication
Sockets are fundamental to this system's communication infrastructure. They provide the endpoint for bidirectional communication between devices.

### What is a Socket?
A socket is a software structure that serves as an endpoint for communication between different processes over a network (in this case, Bluetooth). Think of it like a physical socket on a wall:
- The server creates a "socket outlet"
- Clients create "plugs" that connect to this outlet
- Data flows between them like electricity

## 🎯 Use Cases

1. **Healthcare Facilities**
   - Share patient information with families
   - Broadcast medication schedules
   - Update treatment plans

2. **Educational Institutions**
   - Distribute class materials
   - Share announcements
   - Send assignments and grades

3. **Retail Environments**
   - Update product information
   - Share inventory status
   - Broadcast promotions

4. **Event Management**
   - Real-time schedule updates
   - Attendee information sharing
   - Location-based notifications

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/bluetooth-system.git

# Navigate to project directory
cd bluetooth-system

# Start the server
python src/server.py

# Run the client
python src/client.py
```

## 📋 Requirements

```
python >= 3.8
```

## Workflow 
![Bot Workflow](https://github.com/user-attachments/assets/8a85595a-c31c-4910-a4d4-c8eae3aa5119)

## 💡 Features

### Server Application
- Real-time data broadcasting
- Multi-client support
- Custom data structure support
- Event logging and monitoring
- Automated data synchronization

### Client Application
- Auto-discovery of nearby servers
- Real-time data reception
- Offline data storage
- Customizable UI
- Battery-efficient operation

## 📈 Technical Specifications

- Maximum concurrent connections: 7 devices
- Effective range: 10-100 meters
- Data transfer rate: Up to 2.1 Mbps
- Battery optimization: Adaptive power management
- Automatic reconnection handling
- Custom data protocol support

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to a seperate branch 
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Open source Bluetooth library contributors
- Early adopters and testers
- Community feedback and suggestions
