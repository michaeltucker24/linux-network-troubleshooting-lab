# Linux Network Troubleshooting Lab

This lab focuses on diagnosing and resolving Linux network connectivity issues in a cloud-based environment. It mirrors common support cases involving unreachable services, blocked ports, and misconfigured security rules.

---

## 🎯 Lab Objective

- Diagnose Linux network connectivity issues
- Analyze traffic flow and firewall behavior
- Understand how cloud security rules affect Linux systems

---

## 🧪 Lab Scenarios

### Scenario 1: SSH Connection Timeout
- VM is running but SSH is unreachable
- Diagnose Security Group/firewall rules
- Restore secure SSH access

### Scenario 2: Service Port Not Reachable
- Web service is running but inaccessible
- Verify listening ports and security rules
- Validate connectivity end-to-end

### Scenario 3: Packet Analysis
- Capture and analyze traffic using Wireshark
- Identify dropped or blocked packets

---

## 🛠️ Tools Used

- Ubuntu Linux
- Azure Virtual Machines
- Network Security Groups
- Wireshark
- netstat, ss, ping, traceroute

---

## 🔍 Troubleshooting Approach

1. Verify service status
2. Confirm port listening
3. Inspect firewall and SG rules
4. Capture traffic
5. Apply targeted fixes

---

## ✅ Outcome

This lab strengthened my ability to isolate network-layer issues affecting Linux systems — a critical skill for Linux support engineers handling customer connectivity problems.

---

## 🚀 Future Enhancements

- Add iptables/ufw rule labs
- Simulate DNS failures
- Add monitoring alerts
