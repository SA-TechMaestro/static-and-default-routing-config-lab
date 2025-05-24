# 🌐 Static and Default Routing Lab – IPv4 & IPv6

This lab demonstrates manual configuration of IPv4 and IPv6 static, default, and floating static routes across two routers (R1 and R2) in a dual-stack environment. It was performed using real Cisco hardware via NetLab, not Packet Tracer.

---

## 🎯 Objectives

- Configure IPv4 and IPv6 addressing on R1 and R2
- Apply static routes, default routes, and floating static routes
- Validate connectivity using `ping`, `show`, and `traceroute`
- Demonstrate failover behavior using administrative distance

---

## 🛠️ Tools & Environment

- Cisco 4221 Routers with IOS XE 16.9.4
- Cisco Catalyst 2960 Switches with IOS 15.2(2)
- Remote lab access via NetLab
- Windows PC terminal client (Tera Term)

---

## 📡 Key Configurations

- IPv4 and IPv6 addresses applied to interfaces
- Static route to peer’s loopback interface
- Static and floating default routes using varying AD values
- Verification using:
  - `show ip route`
  - `show ipv6 route`
  - `traceroute` to remote loopbacks

---

## 🧠 What I Learned

- Manual route configuration and verification
- The role of administrative distance in route failover
- Syntax variations between IPv4 and IPv6 route definitions
- Command-line troubleshooting and route logic

---

## 📁 Repo Contents

| File                      | Description                               |
|---------------------------|-------------------------------------------|
| `report.md`               | Full lab process and results              |
| `configs/`                | Config files from R1 and R2               |
| `images/`                 | Screenshots of routing tables & traceouts |
| `lab-original.odt`        | Original lab submission file              |
