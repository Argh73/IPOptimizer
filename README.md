# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-23 12:37:08 +0330

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
| 198.41.209.94 | 80, 443, 8080 | 51 |
| 198.41.208.120 | 80, 443, 8080 | 51 |
| 198.41.209.94 | 80, 443, 8080 | 51 |
| 198.41.208.120 | 80, 443, 8080 | 51 |
| 198.41.208.213 | 80, 443, 8080 | 52 |
| 198.41.208.213 | 80, 443, 8080 | 52 |
| 198.41.208.159 | 80, 443, 8080 | 54 |
| 198.41.208.253 | 80, 443, 8080 | 54 |
| 198.41.208.159 | 80, 443, 8080 | 54 |
| 198.41.208.253 | 80, 443, 8080 | 54 |
| 141.101.121.241 | 80, 443, 8080 | 158 |
| 104.19.42.1 | 80, 443, 8080 | 161 |
| 104.19.88.235 | 80, 443, 8080 | 162 |
| 172.67.202.184 | 80, 443, 8080 | 164 |
| 104.24.59.26 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b09:c996:4917:a2ad:9456:968f] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:bc75:da:bb3a:9bf:c962] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:863f:86f0:e2d8:e41c:e1ed] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:44d4:57f4:e7f4:3df6:3323] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:c996:4917:a2ad:9456:968f] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:bc75:da:bb3a:9bf:c962] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:863f:86f0:e2d8:e41c:e1ed] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:44d4:57f4:e7f4:3df6:3323] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:c996:4917:a2ad:9456:968f] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:bc75:da:bb3a:9bf:c962] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:863f:86f0:e2d8:e41c:e1ed] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:44d4:57f4:e7f4:3df6:3323] | 80, 443, 8080 | 3 |
| [2606:4700:8ca0:f0c8:a2d5:3628:8f0f:8872] | 80, 443, 8080 | 149 |
| [2606:4700:8ca0:f0c8:a2d5:3628:8f0f:8872] | 80, 443, 8080 | 149 |
| [2606:4700:8ca0:f0c8:a2d5:3628:8f0f:8872] | 80, 443, 8080 | 149 |

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
