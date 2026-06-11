# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-11 14:40:38 +0330

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
| 198.41.208.146 | 80, 443, 8080 | 54 |
| 198.41.208.146 | 80, 443, 8080 | 54 |
| 198.41.209.243 | 80, 443, 8080 | 56 |
| 198.41.209.243 | 80, 443, 8080 | 56 |
| 198.41.208.220 | 80, 443, 8080 | 57 |
| 198.41.208.220 | 80, 443, 8080 | 57 |
| 162.159.36.53 | 80, 443, 8080 | 75 |
| 198.41.223.129 | 80, 443, 8080 | 77 |
| 104.17.91.149 | 80, 443, 8080 | 130 |
| 104.17.133.132 | 80, 443, 8080 | 130 |
| 104.19.236.116 | 80, 443, 8080 | 132 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3:1fa7:a4c:dad0:3a4c:21bf] | 80, 443, 8080 | 1 |
| [2606:4700:3:1fa7:a4c:dad0:3a4c:21bf] | 80, 443, 8080 | 1 |
| [2606:4700:3:1fa7:a4c:dad0:3a4c:21bf] | 80, 443, 8080 | 1 |
| [2606:4700:9b03:d2bc:3323:6ff9:23a7:55ea] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:3f2d:9132:fd66:7409:bc84] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d9ce:372:f908:8e67:3ebb] | 80, 443, 8080 | 3 |
| [2606:4700:9adb:93b0:1691:11cf:4be:8a6c] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d2bc:3323:6ff9:23a7:55ea] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:3f2d:9132:fd66:7409:bc84] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d9ce:372:f908:8e67:3ebb] | 80, 443, 8080 | 3 |
| [2606:4700:9adb:93b0:1691:11cf:4be:8a6c] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d2bc:3323:6ff9:23a7:55ea] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:3f2d:9132:fd66:7409:bc84] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d9ce:372:f908:8e67:3ebb] | 80, 443, 8080 | 3 |
| [2606:4700:9adb:93b0:1691:11cf:4be:8a6c] | 80, 443, 8080 | 3 |

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
