# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-13 05:40:23 +0330

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
| 198.41.208.125 | 80, 443, 8080 | 51 |
| 198.41.208.125 | 80, 443, 8080 | 51 |
| 198.41.208.225 | 80, 443, 8080 | 52 |
| 198.41.208.225 | 80, 443, 8080 | 52 |
| 198.41.209.160 | 80, 443, 8080 | 53 |
| 198.41.209.160 | 80, 443, 8080 | 53 |
| 198.41.209.148 | 80, 443, 8080 | 60 |
| 198.41.209.148 | 80, 443, 8080 | 60 |
| 198.41.208.83 | 80, 443, 8080 | 61 |
| 198.41.208.83 | 80, 443, 8080 | 61 |
| 104.16.216.43 | 80, 443, 8080 | 139 |
| 104.16.0.151 | 80, 443, 8080 | 145 |
| 190.93.244.155 | 80, 443, 8080 | 146 |
| 104.16.240.104 | 80, 443, 8080 | 147 |
| 104.16.10.178 | 80, 443, 8080 | 156 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d75:3dd9:cff6:13bf:6029:22a7] | 80, 443, 8080 | 3 |
| [2606:4700:5c:7d22:93b1:e1b4:8384:e7e6] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:25dc:fd34:d66:f79:77cd] | 80, 443, 8080 | 3 |
| [2606:4700:9769:dca0:3917:2a07:e5d1:fe22] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:3dd9:cff6:13bf:6029:22a7] | 80, 443, 8080 | 3 |
| [2606:4700:5c:7d22:93b1:e1b4:8384:e7e6] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:25dc:fd34:d66:f79:77cd] | 80, 443, 8080 | 3 |
| [2606:4700:9769:dca0:3917:2a07:e5d1:fe22] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:3dd9:cff6:13bf:6029:22a7] | 80, 443, 8080 | 3 |
| [2606:4700:5c:7d22:93b1:e1b4:8384:e7e6] | 80, 443, 8080 | 3 |
| [2606:4700:8d75:25dc:fd34:d66:f79:77cd] | 80, 443, 8080 | 3 |
| [2606:4700:9769:dca0:3917:2a07:e5d1:fe22] | 80, 443, 8080 | 3 |
| [2606:4700:3016:10dd:27e2:62c5:77b6:b1f] | 80, 443, 8080 | 13 |
| [2606:4700:3016:10dd:27e2:62c5:77b6:b1f] | 80, 443, 8080 | 13 |
| [2606:4700:3016:10dd:27e2:62c5:77b6:b1f] | 80, 443, 8080 | 13 |

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
