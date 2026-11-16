# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-16 19:45:54 +0330

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
| 198.41.211.201 | 80, 443, 8080 | 112 |
| 104.17.138.82 | 80, 443, 8080 | 141 |
| 104.19.95.8 | 80, 443, 8080 | 141 |
| 172.65.247.8 | 80, 443, 8080 | 142 |
| 104.16.151.37 | 80, 443, 8080 | 142 |
| 162.159.160.254 | 80, 443, 8080 | 155 |
| 162.159.160.254 | 80, 443, 8080 | 155 |
| 162.159.160.51 | 80, 443, 8080 | 157 |
| 162.159.160.196 | 80, 443, 8080 | 157 |
| 162.159.160.51 | 80, 443, 8080 | 157 |
| 162.159.160.196 | 80, 443, 8080 | 157 |
| 162.159.152.97 | 80, 443, 8080 | 162 |
| 162.159.152.97 | 80, 443, 8080 | 162 |
| 162.159.134.64 | 80, 443, 8080 | 163 |
| 162.159.134.64 | 80, 443, 8080 | 163 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b00:ec57:31ed:50ab:4c06:12d0] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:7b7:599b:134d:1423:3cbc] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:ed3f:1c86:ad2:5cf5:489b] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:e543:e541:da0c:ab11:4ed] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:12a7:12c6:3369:eebd:edcf] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:ec57:31ed:50ab:4c06:12d0] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:7b7:599b:134d:1423:3cbc] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:ed3f:1c86:ad2:5cf5:489b] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:e543:e541:da0c:ab11:4ed] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:12a7:12c6:3369:eebd:edcf] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:ec57:31ed:50ab:4c06:12d0] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:7b7:599b:134d:1423:3cbc] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:ed3f:1c86:ad2:5cf5:489b] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:e543:e541:da0c:ab11:4ed] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:12a7:12c6:3369:eebd:edcf] | 80, 443, 8080 | 3 |

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
