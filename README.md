# 🗨️ ChatterX

**Real-Time Chat App with Direct Messaging, Group Chat, and AI Assistant**  
Built with ASP.NET Core + SignalR + Blazor + Azure

---

## 🎯 Project Overview

ChatterX is a modular microservice-style chat platform designed for workshop and demo purposes.  
It showcases real-time communication, clean architecture, and cloud deployment using ASP.NET Core technologies.

---

## 🛠️ Technologies Used

- ASP.NET Core Web API (ChatterX.Api)
- ASP.NET Core SignalR (ChatterX.SignalR)
- Blazor WebAssembly Frontend (ChatterX.BlazorUI + Client)
- Shared Models Library (ChatterX.Shared)
- Azure OpenAI or OpenAI API for AI Assistant
- Azure App Services for cloud deployment

---

## 📦 Solution Structure

ChatterX
├── ChatterX.sln
├── ChatterX.Api → Web API backend
├── ChatterX.SignalR → Real-time messaging (SignalR Hub)
├── ChatterX.BlazorUI → Blazor host project
├── ChatterX.BlazorUI.Client → Blazor WASM frontend
├── ChatterX.Shared → Shared DTOs, Models
├── ChatterX.Tests → Unit and Integration Tests
├── deploy/ → Deployment scripts / pipelines
├── docs/ → Workshop and architecture guides


---

## 🚀 Features

- ✅ Real-time **Direct Messaging (1:1)**
- ✅ Real-time **Group Chat**
- ✅ **AI Assistant Chat** (via OpenAI API)
- ✅ Modern Blazor UI
- ✅ Fully decoupled architecture
- ✅ Ready for Azure cloud deployment

---

## 💻 Local Development Setup

1️⃣ Clone the repository:
```bash
git clone https://github.com/levanijintcharadze/ChatterX.git
cd ChatterX

2️⃣ Build the solution:
dotnet build

3️⃣ Run projects individually:
- Start ChatterX.Api
- Start ChatterX.SignalR
- Start ChatterX.BlazorUI

4️⃣ Open browser:
https://localhost:5001/

## ⚙️ AI Assistant Setup (Optional)

To enable AI Chat:
1. Get your OpenAI or Azure OpenAI API key.
2. Add key to ChatterX.Api configuration:

"OpenAI": {
  "ApiKey": "YOUR_API_KEY_HERE"
}

## 📄 License

This project is licensed under the MIT License. See LICENSE for details.

## 🙌 Credits

This project was prepared as a learning workshop example for ASP.NET Core + SignalR + Blazor + Azure.

## ⭐ Contact

Maintained by Levan Jintcharadze