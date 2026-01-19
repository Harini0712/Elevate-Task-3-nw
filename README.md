# DevOps Internship – Task 3: Networking Basics

## 📌 Objective
To understand basic networking concepts used in DevOps by performing hands-on Linux networking commands and observing system behavior.

---

## 🛠 Tools Used
- Linux CLI (Ubuntu – WSL environment)
- Commands: `ip`, `ping`, `ss`, `nslookup`, `dig`, `traceroute`

---

## ✅ Tasks Completed

### 1️⃣ IP Address and Interface Identification
- Used `ip link` and `ip a` to list available network interfaces.
- Identified `eth0` as the active network interface.
- Learned the difference between `UP/DOWN` state and IP assignment.

---

### 2️⃣ Connectivity Testing
- Used `ping google.com` to test network connectivity.
- Observed `Network is unreachable` due to environment limitations.

---

### 3️⃣ DNS Resolution
- Attempted to use `nslookup` and `dig` for DNS testing.
- Observed that `nslookup` was not available by default.
- Learned that DNS tools require internet connectivity and package installation.

---

### 4️⃣ Open Ports Inspection
- Used `ss -tuln` to view listening TCP and UDP ports.
- Understood how services listen on specific ports.

---

### 5️⃣ Network Path Tracing
- Learned the purpose of `traceroute` to trace packet paths.
- Understood how routing issues can be diagnosed.

---

### 6️⃣ Simulating Network Failure (Hands-On)
- Simulated network failure using:
  ```bash
  sudo ip link set eth0 down
