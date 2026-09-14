# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-15 02:47:43 +0330

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
| 198.41.208.198 | 80, 443, 8080 | 44 |
| 198.41.208.198 | 80, 443, 8080 | 44 |
| 198.41.209.206 | 80, 443, 8080 | 48 |
| 198.41.208.81 | 80, 443, 8080 | 48 |
| 198.41.209.176 | 80, 443, 8080 | 48 |
| 198.41.209.206 | 80, 443, 8080 | 48 |
| 198.41.208.81 | 80, 443, 8080 | 48 |
| 198.41.209.176 | 80, 443, 8080 | 48 |
| 198.41.208.231 | 80, 443, 8080 | 49 |
| 198.41.208.231 | 80, 443, 8080 | 49 |
| 104.17.252.75 | 80, 443, 8080 | 138 |
| 104.17.128.232 | 80, 443, 8080 | 138 |
| 104.19.54.82 | 80, 443, 8080 | 139 |
| 104.18.121.228 | 80, 443, 8080 | 139 |
| 104.17.71.218 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a97:ad8f:bd6d:8f48:8cec:b7eb] | 80, 443, 8080 | 3 |
| [2606:4700:9a97:9417:122e:1414:34e9:1973] | 80, 443, 8080 | 3 |
| [2606:4700:9a97:ad8f:bd6d:8f48:8cec:b7eb] | 80, 443, 8080 | 3 |
| [2606:4700:9a97:9417:122e:1414:34e9:1973] | 80, 443, 8080 | 3 |
| [2606:4700:9a97:ad8f:bd6d:8f48:8cec:b7eb] | 80, 443, 8080 | 3 |
| [2606:4700:9a97:9417:122e:1414:34e9:1973] | 80, 443, 8080 | 3 |
| [2606:4700:8deb:b54c:2aa9:4266:e4b7:6b84] | 80, 443, 8080 | 4 |
| [2606:4700:8393:f4db:a4be:330d:3b30:88e1] | 80, 443, 8080 | 4 |
| [2606:4700:8deb:b54c:2aa9:4266:e4b7:6b84] | 80, 443, 8080 | 4 |
| [2606:4700:8393:f4db:a4be:330d:3b30:88e1] | 80, 443, 8080 | 4 |
| [2606:4700:8deb:b54c:2aa9:4266:e4b7:6b84] | 80, 443, 8080 | 4 |
| [2606:4700:8393:f4db:a4be:330d:3b30:88e1] | 80, 443, 8080 | 4 |
| [2606:4700:8ca0:1725:c6db:5cb4:c1ca:a9b6] | 80, 443, 8080 | 134 |
| [2606:4700:8ca0:1725:c6db:5cb4:c1ca:a9b6] | 80, 443, 8080 | 134 |
| [2606:4700:8ca0:1725:c6db:5cb4:c1ca:a9b6] | 80, 443, 8080 | 134 |

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
