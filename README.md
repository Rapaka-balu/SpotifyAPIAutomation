
# SpotifyAPIAutomation

# 🎧 Spotify API Automation Framework

This project automates the testing of Spotify Web API endpoints using **Java**, **Rest Assured**, **TestNG**, and **JMeter**. It covers both **functional** and **non-functional** testing layers, making it a comprehensive testing suite for backend services.

---

## 🛠️ Tech Stack

- **Language:** Java  
- **Test Framework:** TestNG  
- **HTTP Client:** Rest Assured  
- **Reporting:** ExtentReports  
- **Performance Testing:** Apache JMeter  
- **Build Tool:** Maven

---

## 📋 Features

- 🔐 Secure token management via `TokenManager`
- ✅ Automated test cases for:
  - Create Playlist
  - Add Track to Playlist
  - Get Playlist Details
  - Update Playlist
  - Remove Track from Playlist
- 🔁 Token refresh handling
- 📊 Performance testing via JMeter

---

## ✅ Levels of Testing Covered

| Level               | Type                         | Status   |
|--------------------|------------------------------|----------|
| 1️⃣ Integration     | Spotify API endpoint linking | ✅ Done   |
| 2️⃣ System          | End-to-end test coverage     | ✅ Done   |
| 3️⃣ Sanity          | Basic health-check endpoints | ✅ Done   |
| 4️⃣ Smoke           | Stability on major endpoints | ✅ Done   |
| 5️⃣ Regression      | Re-tested after bug fixes    | ✅ Done   |
| 6️⃣ Negative        | Invalid input and auth tests | ✅ Done   |
| 7️⃣ Security (Basic)| Auth scope, 401/403 handling | ✅ Done   |
| 8️⃣ Load Testing    | With JMeter threads          | ✅ Done   |
| 9️⃣ Stress Testing  | Pushed API limits (429 error)| ✅ Done   |
| 🔟 Performance      | Avg. response time, latency  | ✅ Done   |

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/spotify-api-automation.git
