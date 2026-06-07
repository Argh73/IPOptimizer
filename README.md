# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-08 01:13:44 +0330

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
| 162.159.46.20 | 80, 443, 8080 | 73 |
| 162.159.46.20 | 80, 443, 8080 | 73 |
| 162.159.46.20 | 80, 443, 8080 | 73 |
| 104.19.20.212 | 80, 443, 8080 | 129 |
| 104.19.20.212 | 80, 443, 8080 | 129 |
| 104.19.20.212 | 80, 443, 8080 | 129 |
| 104.17.228.155 | 80, 443, 8080 | 130 |
| 104.17.228.155 | 80, 443, 8080 | 130 |
| 104.17.228.155 | 80, 443, 8080 | 130 |
| 104.19.171.155 | 80, 443, 8080 | 131 |
| 104.19.171.155 | 80, 443, 8080 | 131 |
| 104.19.171.155 | 80, 443, 8080 | 131 |
| 104.17.158.175 | 80, 443, 8080 | 132 |
| 104.17.158.175 | 80, 443, 8080 | 132 |
| 104.17.158.175 | 80, 443, 8080 | 132 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8394:f38:8b5e:e39c:bdeb:940a] | 80, 443, 8080 | 1 |
| [2606:4700:8394:f38:8b5e:e39c:bdeb:940a] | 80, 443, 8080 | 1 |
| [2606:4700:8394:f38:8b5e:e39c:bdeb:940a] | 80, 443, 8080 | 1 |
| [2606:4700:8d77:5882:ee97:1d8d:6dfd:211d] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:5882:ee97:1d8d:6dfd:211d] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:5882:ee97:1d8d:6dfd:211d] | 80, 443, 8080 | 3 |
| [2606:4700:1d:4d46:b173:129f:e3f9:46f1] | 80, 443, 8080 | 13 |
| [2606:4700:1d:fe60:adb3:cd49:41fd:cec3] | 80, 443, 8080 | 13 |
| [2606:4700:1d:4d46:b173:129f:e3f9:46f1] | 80, 443, 8080 | 13 |
| [2606:4700:1d:fe60:adb3:cd49:41fd:cec3] | 80, 443, 8080 | 13 |
| [2606:4700:1d:4d46:b173:129f:e3f9:46f1] | 80, 443, 8080 | 13 |
| [2606:4700:1d:fe60:adb3:cd49:41fd:cec3] | 80, 443, 8080 | 13 |
| [2606:4700:83b4:b62e:cc4:ad9f:f414:5a4a] | 80, 443, 8080 | 152 |
| [2606:4700:83b4:b62e:cc4:ad9f:f414:5a4a] | 80, 443, 8080 | 152 |
| [2606:4700:83b4:b62e:cc4:ad9f:f414:5a4a] | 80, 443, 8080 | 152 |

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
