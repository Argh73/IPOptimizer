# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-11 04:15:30 +0330

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
| 198.41.209.113 | 80, 443, 8080 | 49 |
| 198.41.209.113 | 80, 443, 8080 | 49 |
| 198.41.209.71 | 80, 443, 8080 | 51 |
| 198.41.209.32 | 80, 443, 8080 | 51 |
| 198.41.209.71 | 80, 443, 8080 | 51 |
| 198.41.209.32 | 80, 443, 8080 | 51 |
| 198.41.209.182 | 80, 443, 8080 | 59 |
| 198.41.209.182 | 80, 443, 8080 | 59 |
| 198.41.209.217 | 80, 443, 8080 | 82 |
| 198.41.209.217 | 80, 443, 8080 | 82 |
| 104.16.170.4 | 80, 443, 8080 | 138 |
| 104.16.81.87 | 80, 443, 8080 | 139 |
| 104.18.246.197 | 80, 443, 8080 | 139 |
| 104.18.152.53 | 80, 443, 8080 | 139 |
| 104.16.2.60 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c61:c595:8b4c:975f:f2a4:7eac] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:dfc6:6157:fe29:560c:e81f] | 80, 443, 8080 | 3 |
| [2606:4700:3:88dd:2c7e:b934:bafa:b471] | 80, 443, 8080 | 3 |
| [2606:4700:9c61:8f98:c859:3df9:d175:bad3] | 80, 443, 8080 | 3 |
| [2606:4700:9c61:c595:8b4c:975f:f2a4:7eac] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:dfc6:6157:fe29:560c:e81f] | 80, 443, 8080 | 3 |
| [2606:4700:3:88dd:2c7e:b934:bafa:b471] | 80, 443, 8080 | 3 |
| [2606:4700:9c61:8f98:c859:3df9:d175:bad3] | 80, 443, 8080 | 3 |
| [2606:4700:9c61:c595:8b4c:975f:f2a4:7eac] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:dfc6:6157:fe29:560c:e81f] | 80, 443, 8080 | 3 |
| [2606:4700:3:88dd:2c7e:b934:bafa:b471] | 80, 443, 8080 | 3 |
| [2606:4700:9c61:8f98:c859:3df9:d175:bad3] | 80, 443, 8080 | 3 |
| [2606:4700:83b4:6fa2:ba67:b779:9096:81e9] | 80, 443, 8080 | 156 |
| [2606:4700:83b4:6fa2:ba67:b779:9096:81e9] | 80, 443, 8080 | 156 |
| [2606:4700:83b4:6fa2:ba67:b779:9096:81e9] | 80, 443, 8080 | 156 |

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
