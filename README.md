# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-08 03:48:15 +0330

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
| 198.41.209.253 | 80, 443, 8080 | 49 |
| 198.41.209.253 | 80, 443, 8080 | 49 |
| 198.41.209.133 | 80, 443, 8080 | 58 |
| 198.41.209.133 | 80, 443, 8080 | 58 |
| 162.159.36.88 | 80, 443, 8080 | 74 |
| 198.41.209.157 | 80, 443, 8080 | 84 |
| 198.41.209.157 | 80, 443, 8080 | 84 |
| 172.67.155.3 | 80, 443, 8080 | 134 |
| 172.67.158.114 | 80, 443, 8080 | 134 |
| 172.67.155.3 | 80, 443, 8080 | 134 |
| 172.67.158.114 | 80, 443, 8080 | 134 |
| 104.21.224.125 | 80, 443, 8080 | 139 |
| 104.18.194.71 | 80, 443, 8080 | 139 |
| 104.17.71.173 | 80, 443, 8080 | 139 |
| 104.17.183.20 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9aeb:bb28:7c8d:fee6:f569:b3af] | 80, 443, 8080 | 3 |
| [2606:4700:3004:b744:516a:52d3:d8fd:7e47] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:c64e:5d65:5f30:7438:dc5c] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:840c:64b8:8cf6:ec87:8274] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:344a:e141:5a86:5537:a9ab] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:bb28:7c8d:fee6:f569:b3af] | 80, 443, 8080 | 3 |
| [2606:4700:3004:b744:516a:52d3:d8fd:7e47] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:c64e:5d65:5f30:7438:dc5c] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:840c:64b8:8cf6:ec87:8274] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:344a:e141:5a86:5537:a9ab] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:bb28:7c8d:fee6:f569:b3af] | 80, 443, 8080 | 3 |
| [2606:4700:3004:b744:516a:52d3:d8fd:7e47] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:c64e:5d65:5f30:7438:dc5c] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:840c:64b8:8cf6:ec87:8274] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:344a:e141:5a86:5537:a9ab] | 80, 443, 8080 | 3 |

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
