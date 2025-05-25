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

- Configured dual-stack (IPv4 + IPv6) addressing on:
  - GigabitEthernet interfaces (G0/0/0, G0/0/1)
  - Two loopbacks per router
- Applied static routes for:
  - Private loopback networks (10.x.x.x and 2001:db8:acad:10::/11::)
  - Public address simulation ranges (209.165.200.x and matching IPv6)
- Configured default and floating static routes for failover
- Validated connectivity with:
  - `ping`
  - `traceroute`
  - `show ip route` / `show ipv6 route`

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
| `configs/`                | Basic Router/Switch Config files          |
| `images/`                 | Screenshots of routing tables & traceouts |
| `lab-original.odt`        | Original lab submission file              |
