# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-28 03:24:18 +0330

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
| 198.41.208.208 | 80, 443, 8080 | 48 |
| 198.41.208.208 | 80, 443, 8080 | 48 |
| 198.41.208.76 | 80, 443, 8080 | 49 |
| 198.41.208.76 | 80, 443, 8080 | 49 |
| 198.41.209.17 | 80, 443, 8080 | 51 |
| 198.41.209.17 | 80, 443, 8080 | 51 |
| 198.41.208.143 | 80, 443, 8080 | 53 |
| 198.41.208.143 | 80, 443, 8080 | 53 |
| 104.17.89.156 | 80, 443, 8080 | 138 |
| 104.16.228.170 | 80, 443, 8080 | 139 |
| 104.17.124.145 | 80, 443, 8080 | 139 |
| 104.17.102.168 | 80, 443, 8080 | 139 |
| 104.17.125.138 | 80, 443, 8080 | 139 |
| 162.159.160.129 | 80, 443, 8080 | 145 |
| 162.159.160.129 | 80, 443, 8080 | 145 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a94:efca:c057:287b:d14e:80f9] | 80, 443, 8080 | 3 |
| [2606:4700:3005:d4c2:dfbf:cb53:c2d0:3b57] | 80, 443, 8080 | 3 |
| [2606:4700:9a6c:5b1f:92d0:64e9:367b:e1c8] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:efca:c057:287b:d14e:80f9] | 80, 443, 8080 | 3 |
| [2606:4700:3005:d4c2:dfbf:cb53:c2d0:3b57] | 80, 443, 8080 | 3 |
| [2606:4700:9a6c:5b1f:92d0:64e9:367b:e1c8] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:efca:c057:287b:d14e:80f9] | 80, 443, 8080 | 3 |
| [2606:4700:3005:d4c2:dfbf:cb53:c2d0:3b57] | 80, 443, 8080 | 3 |
| [2606:4700:9a6c:5b1f:92d0:64e9:367b:e1c8] | 80, 443, 8080 | 3 |
| [2606:4700:133:55df:d215:3507:1d15:7ad3] | 80, 443, 8080 | 12 |
| [2606:4700:133:55df:d215:3507:1d15:7ad3] | 80, 443, 8080 | 12 |
| [2606:4700:133:55df:d215:3507:1d15:7ad3] | 80, 443, 8080 | 12 |
| [2606:4700:3005:4562:d3:3d2e:f40:efac] | 80, 443, 8080 | 13 |
| [2606:4700:3005:4562:d3:3d2e:f40:efac] | 80, 443, 8080 | 13 |
| [2606:4700:3005:4562:d3:3d2e:f40:efac] | 80, 443, 8080 | 13 |

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
