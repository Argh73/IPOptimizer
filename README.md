# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-27 03:28:24 +0330

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
| 198.41.208.40 | 80, 443, 8080 | 46 |
| 198.41.208.40 | 80, 443, 8080 | 46 |
| 198.41.209.26 | 80, 443, 8080 | 47 |
| 198.41.209.26 | 80, 443, 8080 | 47 |
| 198.41.209.202 | 80, 443, 8080 | 51 |
| 198.41.209.48 | 80, 443, 8080 | 51 |
| 198.41.209.202 | 80, 443, 8080 | 51 |
| 198.41.209.48 | 80, 443, 8080 | 51 |
| 198.41.209.110 | 80, 443, 8080 | 53 |
| 198.41.209.110 | 80, 443, 8080 | 53 |
| 198.41.211.104 | 80, 443, 8080 | 72 |
| 104.19.173.174 | 80, 443, 8080 | 138 |
| 104.19.96.90 | 80, 443, 8080 | 139 |
| 104.17.92.172 | 80, 443, 8080 | 139 |
| 104.18.12.9 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:440f:54e0:5604:a2c3:162d:8419] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:4c3c:32ec:2adf:da4e:ed37] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:eb07:5b4c:52f3:5072:ccca] | 80, 443, 8080 | 3 |
| [2606:4700:440f:2b8:7d65:539c:c22e:9fda] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:7c07:d3a2:f390:f216:52ec] | 80, 443, 8080 | 3 |
| [2606:4700:440f:54e0:5604:a2c3:162d:8419] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:4c3c:32ec:2adf:da4e:ed37] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:eb07:5b4c:52f3:5072:ccca] | 80, 443, 8080 | 3 |
| [2606:4700:440f:2b8:7d65:539c:c22e:9fda] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:7c07:d3a2:f390:f216:52ec] | 80, 443, 8080 | 3 |
| [2606:4700:440f:54e0:5604:a2c3:162d:8419] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:4c3c:32ec:2adf:da4e:ed37] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:eb07:5b4c:52f3:5072:ccca] | 80, 443, 8080 | 3 |
| [2606:4700:440f:2b8:7d65:539c:c22e:9fda] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:7c07:d3a2:f390:f216:52ec] | 80, 443, 8080 | 3 |

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
