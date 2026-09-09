# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-09 15:13:35 +0330

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
| 198.41.209.152 | 80, 443, 8080 | 49 |
| 198.41.209.152 | 80, 443, 8080 | 49 |
| 198.41.209.193 | 80, 443, 8080 | 50 |
| 198.41.209.193 | 80, 443, 8080 | 50 |
| 198.41.209.52 | 80, 443, 8080 | 52 |
| 198.41.209.52 | 80, 443, 8080 | 52 |
| 198.41.209.101 | 80, 443, 8080 | 53 |
| 198.41.209.101 | 80, 443, 8080 | 53 |
| 198.41.208.19 | 80, 443, 8080 | 60 |
| 198.41.208.19 | 80, 443, 8080 | 60 |
| 104.19.139.24 | 80, 443, 8080 | 141 |
| 104.16.168.131 | 80, 443, 8080 | 141 |
| 104.18.99.216 | 80, 443, 8080 | 141 |
| 104.16.240.183 | 80, 443, 8080 | 143 |
| 104.18.155.165 | 80, 443, 8080 | 152 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:4400:3c2b:fc83:e558:503:aab0] | 80, 443, 8080 | 3 |
| [2606:4700:4400:3c2b:fc83:e558:503:aab0] | 80, 443, 8080 | 3 |
| [2606:4700:4400:3c2b:fc83:e558:503:aab0] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:d2a:fb2a:5cf8:6e14:a98a] | 80, 443, 8080 | 4 |
| [2606:4700:8d78:d2a:fb2a:5cf8:6e14:a98a] | 80, 443, 8080 | 4 |
| [2606:4700:8d78:d2a:fb2a:5cf8:6e14:a98a] | 80, 443, 8080 | 4 |
| [2606:4700:3011:b063:ac92:c6d5:49ad:221a] | 80, 443, 8080 | 13 |
| [2606:4700:3011:b063:ac92:c6d5:49ad:221a] | 80, 443, 8080 | 13 |
| [2606:4700:3011:b063:ac92:c6d5:49ad:221a] | 80, 443, 8080 | 13 |
| [2606:4700:83b3:2375:ae1:a912:17fc:fccf] | 80, 443, 8080 | 145 |
| [2606:4700:83b3:2375:ae1:a912:17fc:fccf] | 80, 443, 8080 | 145 |
| [2606:4700:83b3:2375:ae1:a912:17fc:fccf] | 80, 443, 8080 | 145 |
| [2606:4700:83b3:a571:5351:98d3:4947:84bd] | 80, 443, 8080 | 156 |
| [2606:4700:83b3:a571:5351:98d3:4947:84bd] | 80, 443, 8080 | 156 |
| [2606:4700:83b3:a571:5351:98d3:4947:84bd] | 80, 443, 8080 | 156 |

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
