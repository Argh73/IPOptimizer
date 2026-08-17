# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-18 00:23:23 +0330

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
| 198.41.209.180 | 80, 443, 8080 | 52 |
| 198.41.209.180 | 80, 443, 8080 | 52 |
| 198.41.209.52 | 80, 443, 8080 | 53 |
| 198.41.209.52 | 80, 443, 8080 | 53 |
| 198.41.208.165 | 80, 443, 8080 | 54 |
| 198.41.209.123 | 80, 443, 8080 | 54 |
| 198.41.208.165 | 80, 443, 8080 | 54 |
| 198.41.209.123 | 80, 443, 8080 | 54 |
| 198.41.208.0 | 80, 443, 8080 | 57 |
| 198.41.208.0 | 80, 443, 8080 | 57 |
| 104.21.224.166 | 80, 443, 8080 | 138 |
| 104.19.18.165 | 80, 443, 8080 | 139 |
| 104.17.25.251 | 80, 443, 8080 | 139 |
| 104.19.217.73 | 80, 443, 8080 | 139 |
| 104.19.7.98 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:101:91c:832e:90a4:cd3:b4e2] | 80, 443, 8080 | 0 |
| [2606:4700:101:91c:832e:90a4:cd3:b4e2] | 80, 443, 8080 | 0 |
| [2606:4700:101:91c:832e:90a4:cd3:b4e2] | 80, 443, 8080 | 0 |
| [2606:4700:8d79:ed:6194:58ed:953d:fb25] | 80, 443, 8080 | 1 |
| [2606:4700:8d79:b008:8a2d:1704:8818:a88] | 80, 443, 8080 | 1 |
| [2606:4700:8d79:ed:6194:58ed:953d:fb25] | 80, 443, 8080 | 1 |
| [2606:4700:8d79:b008:8a2d:1704:8818:a88] | 80, 443, 8080 | 1 |
| [2606:4700:8d79:ed:6194:58ed:953d:fb25] | 80, 443, 8080 | 1 |
| [2606:4700:8d79:b008:8a2d:1704:8818:a88] | 80, 443, 8080 | 1 |
| [2606:4700:9a9f:befb:6a06:e07c:5d64:b01b] | 80, 443, 8080 | 3 |
| [2606:4700:9763:abcd:a6b6:7cdc:86ce:b98d] | 80, 443, 8080 | 3 |
| [2606:4700:9a9f:befb:6a06:e07c:5d64:b01b] | 80, 443, 8080 | 3 |
| [2606:4700:9763:abcd:a6b6:7cdc:86ce:b98d] | 80, 443, 8080 | 3 |
| [2606:4700:9a9f:befb:6a06:e07c:5d64:b01b] | 80, 443, 8080 | 3 |
| [2606:4700:9763:abcd:a6b6:7cdc:86ce:b98d] | 80, 443, 8080 | 3 |

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
