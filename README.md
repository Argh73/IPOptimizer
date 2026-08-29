# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-29 16:17:17 +0330

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
| 104.17.34.13 | 80, 443, 8080 | 140 |
| 104.17.34.13 | 80, 443, 8080 | 140 |
| 104.17.34.13 | 80, 443, 8080 | 140 |
| 104.19.77.19 | 80, 443, 8080 | 142 |
| 104.19.77.19 | 80, 443, 8080 | 142 |
| 104.19.77.19 | 80, 443, 8080 | 142 |
| 104.17.246.229 | 80, 443, 8080 | 144 |
| 104.17.246.229 | 80, 443, 8080 | 144 |
| 104.17.246.229 | 80, 443, 8080 | 144 |
| 104.19.62.6 | 80, 443, 8080 | 148 |
| 104.19.62.6 | 80, 443, 8080 | 148 |
| 104.19.62.6 | 80, 443, 8080 | 148 |
| 104.18.179.188 | 80, 443, 8080 | 150 |
| 104.18.179.188 | 80, 443, 8080 | 150 |
| 104.18.179.188 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:130:25b3:a102:2f82:cd33:41b5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:7943:4fcf:da06:6fe6:2ea1] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:6ef4:b9b9:855c:2488:a3d5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:1b8f:b147:a9b2:22d9:91a1] | 80, 443, 8080 | 3 |
| [2606:4700:130:25b3:a102:2f82:cd33:41b5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:7943:4fcf:da06:6fe6:2ea1] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:6ef4:b9b9:855c:2488:a3d5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:1b8f:b147:a9b2:22d9:91a1] | 80, 443, 8080 | 3 |
| [2606:4700:130:25b3:a102:2f82:cd33:41b5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:7943:4fcf:da06:6fe6:2ea1] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:6ef4:b9b9:855c:2488:a3d5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:1b8f:b147:a9b2:22d9:91a1] | 80, 443, 8080 | 3 |
| [2606:4700:130:b6dd:c03b:cd42:3192:2164] | 80, 443, 8080 | 12 |
| [2606:4700:130:b6dd:c03b:cd42:3192:2164] | 80, 443, 8080 | 12 |
| [2606:4700:130:b6dd:c03b:cd42:3192:2164] | 80, 443, 8080 | 12 |

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
