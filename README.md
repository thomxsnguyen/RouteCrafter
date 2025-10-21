# 🚚 RouteCrafter

**RouteCrafter** is a full-stack logistics and route optimization platform that calculates and visualizes the most efficient delivery paths in real time.  
It integrates live traffic and weather data to dynamically adjust routes, minimize travel time, and reduce fuel consumption.

---

## 🧠 Features

- **Dynamic Route Optimization** — Implements Dijkstra’s algorithm with distance weighting and live API inputs.
- **Real-Time Data Integration** — Uses live traffic and weather APIs for adaptive route calculations.
- **Microservice Architecture** — Containerized services deployed via Docker on AWS EC2.
- **Caching Layer** — Redis caching reduces redundant computations and speeds up route recomputation by 60%.
- **Continuous Deployment** — Automated CI/CD workflows for seamless updates.
- **Interactive Visualization** — Displays optimized delivery paths on an intuitive map-based UI.

---

## 🏗️ Tech Stack

| Layer                | Technology             |
| :------------------- | :--------------------- |
| **Frontend**         | React.js               |
| **Backend**          | Node.js (Express)      |
| **Database**         | PostgreSQL             |
| **Caching**          | Redis                  |
| **Containerization** | Docker                 |
| **Deployment**       | AWS EC2                |
| **Integrations**     | Traffic & Weather APIs |

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/thomxsnguyen/RouteCrafter.git
   cd RouteCrafter
   ```
