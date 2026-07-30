# Hi, I'm Ionela-Valentina Dică 👋

I am a Computer Engineering graduate interested in full-stack development, backend systems, databases, networking, and cybersecurity.

I enjoy building practical applications using technologies such as React, FastAPI, PostgreSQL, C#, .NET, and Docker.

## Featured Projects

### 🎓 [UniAttendance](https://github.com/ioneladd/UniAttendancee)

A full-stack web application for managing and monitoring student attendance at university courses and events.

Teachers can create courses and attendance sessions, while students register their attendance by scanning a dynamic QR code. The QR code is regenerated every three seconds to reduce unauthorized sharing.

#### Key Features

- role-based access for teachers, students, visitors, and administrators;
- dynamic QR codes for attendance registration;
- real-time attendance updates using WebSockets;
- course enrollment using generated codes;
- manual attendance management;
- participation tracking for events and additional activities;
- secure authentication with Firebase.

#### Technologies

`React` `Vite` `Tailwind CSS` `Python` `FastAPI` `WebSockets` `PostgreSQL` `Supabase` `Firebase` `Docker`

[Live Demo](https://uniattendance.vercel.app/) · [Backend API](https://uniattendance.onrender.com/api) · [Source Code](https://github.com/ioneladd/UniAttendancee)

---

### 📡 [GSM Wake-on-LAN](https://github.com/ioneladd/GSM_WoL)

A Windows Service that communicates with a GSM modem through a serial port and remotely wakes network devices using Wake-on-LAN magic packets.

The service can be triggered by an authorized phone call or SMS message.

#### How It Works

```text
Phone call or SMS
        │
        ▼
GSM modem
        │
        ▼
GSM Wake-on-LAN Windows Service
        │
        ├── Phone call → identifies the caller → sends a WoL packet
        │
        └── SMS → identifies the requested test bench → sends a WoL packet
```

#### Key Features

- communication with a GSM modem using AT commands;
- caller identification using the `+CLIP` command;
- SMS message processing;
- authorized user validation;
- Wake-on-LAN magic packet generation;
- configurable users and devices through `App.config`;
- background execution as a Windows Service;
- logging of unauthorized access attempts.

#### Technologies

`C#` `.NET 6` `Windows Services` `Serial Communication` `AT Commands` `Wake-on-LAN` `UDP`

[Source Code](https://github.com/ioneladd/GSM_WoL)



## Technologies and Tools

### Frontend

- React
- JavaScript
- HTML
- CSS
- Tailwind CSS
- Vite

### Backend

- Python
- FastAPI
- C#
- .NET
- REST APIs
- WebSockets

### Databases and Cloud Services

- PostgreSQL
- Supabase
- Firebase
- Vercel
- Render

### Development Tools

- Git
- GitHub
- Docker
- Visual Studio
- Visual Studio Code
- Postman

## Currently Learning

- cybersecurity;
- network security;
- secure web application development.

## Contact

- LinkedIn: [Ionela-Valentina Dică](https://www.linkedin.com/in/ionela-valentina-dic%C4%83-368b8038b/)
- Email: `ioneladica779@gmail.com`
