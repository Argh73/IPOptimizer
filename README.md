# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-16 00:17:05 +0330

**JSON Files**: The `ipv4.json`, `ipv6.json`, and `export.json` files are available in the [Releases section](https://github.com/Argh94/IPOptimizer/releases).

## ✨ Features
- 📡 **Low-Latency IPs**: Sorted by lowest latency.
- 🔍 **Suggested Ports**: Open ports (80, 443, 8080) are automatically checked.
- ⏰ **Regular Updates**: Every 5 hours via GitHub Actions.
- 📄 **JSON Outputs**: Data is stored in the Releases section (`ipv4.json`, `ipv6.json`, `export.json`).

## 📋 Optimized IPs

**Note:** The displayed ports have been checked by the server, but they may vary depending on your network. For verification, use [YouGetSignal](https://www.yougetsignal.com/tools/open-ports/) (IPv4) or [Nmap](https://nmap.org/) (IPv6).

### IPv4
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| 198.41.208.111 | 80, 443, 8080 | 56 |
| 198.41.208.111 | 80, 443, 8080 | 56 |
| 198.41.209.24 | 80, 443, 8080 | 57 |
| 198.41.209.24 | 80, 443, 8080 | 57 |
| 198.41.209.175 | 80, 443, 8080 | 59 |
| 198.41.209.175 | 80, 443, 8080 | 59 |
| 198.41.209.168 | 80, 443, 8080 | 61 |
| 198.41.209.168 | 80, 443, 8080 | 61 |
| 198.41.211.221 | 80, 443, 8080 | 71 |
| 104.17.80.174 | 80, 443, 8080 | 138 |
| 104.17.85.195 | 80, 443, 8080 | 138 |
| 104.17.238.173 | 80, 443, 8080 | 139 |
| 104.18.93.108 | 80, 443, 8080 | 140 |
| 172.67.65.19 | 80, 443, 8080 | 193 |
| 172.67.65.19 | 80, 443, 8080 | 193 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91bc:c77f:50f8:3bca:ef89:ce16] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:8295:7aaf:ad53:fd1b:4c28] | 80, 443, 8080 | 3 |
| [2606:4700:8393:c3:4cb4:34ed:175c:7665] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:b821:b319:a772:f82:c88c] | 80, 443, 8080 | 3 |
| [2606:4700:3023:5f8a:4335:a3e0:8470:8d63] | 80, 443, 8080 | 3 |
| [2606:4700:91bc:c77f:50f8:3bca:ef89:ce16] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:8295:7aaf:ad53:fd1b:4c28] | 80, 443, 8080 | 3 |
| [2606:4700:8393:c3:4cb4:34ed:175c:7665] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:b821:b319:a772:f82:c88c] | 80, 443, 8080 | 3 |
| [2606:4700:3023:5f8a:4335:a3e0:8470:8d63] | 80, 443, 8080 | 3 |
| [2606:4700:91bc:c77f:50f8:3bca:ef89:ce16] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:8295:7aaf:ad53:fd1b:4c28] | 80, 443, 8080 | 3 |
| [2606:4700:8393:c3:4cb4:34ed:175c:7665] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:b821:b319:a772:f82:c88c] | 80, 443, 8080 | 3 |
| [2606:4700:3023:5f8a:4335:a3e0:8470:8d63] | 80, 443, 8080 | 3 |

## 🛠️ Installation and Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Argh94/IPOptimizer.git
   ```
2. **PHP Setup**:
   - Install PHP 8.0 or higher.
   - Set the Hostmonit API key in the `HOSTMONIT_API_KEY` environment variable:
     ```bash
     export HOSTMONIT_API_KEY="your-api-key"
     ```
3. **Run the Script**:
   ```bash
   php scripts/fetch_ips.php
   ```
4. **Check Output**:
   - JSON files are available in the [Releases section](https://github.com/Argh94/IPOptimizer/releases).
   - IP list in `README.md`.

## 📬 Support
- 🐛 **Report Issues**: [Issues](https://github.com/Argh94/IPOptimizer/issues)
- 📧 **Contact**: [ircfspace@gmail.com](mailto:ircfspace@gmail.com)

## 📄 License
This project is licensed under the [MIT License](https://github.com/Argh94/HandWave/blob/main/LICENCE).
