# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-19 00:19:03 +0330

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
| 198.41.211.172 | 80, 443, 8080 | 72 |
| 198.41.211.229 | 80, 443, 8080 | 88 |
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 104.21.236.248 | 80, 443, 8080 | 138 |
| 104.17.174.70 | 80, 443, 8080 | 138 |
| 104.16.242.148 | 80, 443, 8080 | 139 |
| 198.41.209.1 | 80, 443, 8080 | 167 |
| 198.41.209.1 | 80, 443, 8080 | 167 |
| 172.67.167.165 | 80, 443, 8080 | 190 |
| 172.67.167.165 | 80, 443, 8080 | 190 |
| 162.159.160.152 | 80, 443, 8080 | 192 |
| 162.159.160.152 | 80, 443, 8080 | 192 |
| 172.67.121.50 | 80, 443, 8080 | 201 |
| 172.67.121.50 | 80, 443, 8080 | 201 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90cf:d193:db12:a83c:4451:e72d] | 80, 443, 8080 | 3 |
| [2606:4700:3009:2b89:46a5:f851:2382:aabd] | 80, 443, 8080 | 3 |
| [2606:4700:9643:34a7:ce3c:efeb:b7e4:cd3e] | 80, 443, 8080 | 3 |
| [2606:4700:839c:cac9:5aa5:eba5:1c41:c1ac] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:b01f:cf26:d859:1752:877b] | 80, 443, 8080 | 3 |
| [2606:4700:90cf:d193:db12:a83c:4451:e72d] | 80, 443, 8080 | 3 |
| [2606:4700:3009:2b89:46a5:f851:2382:aabd] | 80, 443, 8080 | 3 |
| [2606:4700:9643:34a7:ce3c:efeb:b7e4:cd3e] | 80, 443, 8080 | 3 |
| [2606:4700:839c:cac9:5aa5:eba5:1c41:c1ac] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:b01f:cf26:d859:1752:877b] | 80, 443, 8080 | 3 |
| [2606:4700:90cf:d193:db12:a83c:4451:e72d] | 80, 443, 8080 | 3 |
| [2606:4700:3009:2b89:46a5:f851:2382:aabd] | 80, 443, 8080 | 3 |
| [2606:4700:9643:34a7:ce3c:efeb:b7e4:cd3e] | 80, 443, 8080 | 3 |
| [2606:4700:839c:cac9:5aa5:eba5:1c41:c1ac] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:b01f:cf26:d859:1752:877b] | 80, 443, 8080 | 3 |

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
