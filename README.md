# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-11 02:12:48 +0330

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
| 198.41.208.228 | 80, 443, 8080 | 47 |
| 198.41.208.186 | 80, 443, 8080 | 47 |
| 198.41.208.228 | 80, 443, 8080 | 47 |
| 198.41.208.186 | 80, 443, 8080 | 47 |
| 198.41.209.3 | 80, 443, 8080 | 50 |
| 198.41.209.3 | 80, 443, 8080 | 50 |
| 198.41.208.233 | 80, 443, 8080 | 51 |
| 198.41.208.233 | 80, 443, 8080 | 51 |
| 198.41.209.23 | 80, 443, 8080 | 81 |
| 198.41.209.23 | 80, 443, 8080 | 81 |
| 162.159.36.141 | 80, 443, 8080 | 89 |
| 198.41.222.223 | 80, 443, 8080 | 90 |
| 198.41.223.169 | 80, 443, 8080 | 91 |
| 104.19.67.182 | 80, 443, 8080 | 138 |
| 104.19.86.92 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d72:5590:78ca:66d3:a21f:cd] | 80, 443, 8080 | 3 |
| [2606:4700:2c:247d:b977:2bee:ad21:6d06] | 80, 443, 8080 | 3 |
| [2606:4700:8d72:5590:78ca:66d3:a21f:cd] | 80, 443, 8080 | 3 |
| [2606:4700:2c:247d:b977:2bee:ad21:6d06] | 80, 443, 8080 | 3 |
| [2606:4700:8d72:5590:78ca:66d3:a21f:cd] | 80, 443, 8080 | 3 |
| [2606:4700:2c:247d:b977:2bee:ad21:6d06] | 80, 443, 8080 | 3 |
| [2606:4700:8d72:5064:be7:e4d3:c3af:f5ab] | 80, 443, 8080 | 6 |
| [2606:4700:8d72:5064:be7:e4d3:c3af:f5ab] | 80, 443, 8080 | 6 |
| [2606:4700:8d72:5064:be7:e4d3:c3af:f5ab] | 80, 443, 8080 | 6 |
| [2606:4700:83b2:bd29:4b68:fe1c:87ed:148] | 80, 443, 8080 | 167 |
| [2606:4700:83b2:71db:d062:1b75:52d7:33de] | 80, 443, 8080 | 167 |
| [2606:4700:83b2:bd29:4b68:fe1c:87ed:148] | 80, 443, 8080 | 167 |
| [2606:4700:83b2:71db:d062:1b75:52d7:33de] | 80, 443, 8080 | 167 |
| [2606:4700:83b2:bd29:4b68:fe1c:87ed:148] | 80, 443, 8080 | 167 |
| [2606:4700:83b2:71db:d062:1b75:52d7:33de] | 80, 443, 8080 | 167 |

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
