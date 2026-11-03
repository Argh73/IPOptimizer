# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-03 18:02:12 +0330

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
| 198.41.209.122 | 80, 443, 8080 | 71 |
| 198.41.209.122 | 80, 443, 8080 | 71 |
| 198.41.209.84 | 80, 443, 8080 | 92 |
| 198.41.209.84 | 80, 443, 8080 | 92 |
| 198.41.209.220 | 80, 443, 8080 | 98 |
| 198.41.209.220 | 80, 443, 8080 | 98 |
| 104.18.107.136 | 80, 443, 8080 | 141 |
| 104.19.205.184 | 80, 443, 8080 | 141 |
| 104.18.178.115 | 80, 443, 8080 | 142 |
| 104.17.108.198 | 80, 443, 8080 | 142 |
| 104.21.235.50 | 80, 443, 8080 | 142 |
| 162.159.137.224 | 80, 443, 8080 | 164 |
| 162.159.130.71 | 80, 443, 8080 | 164 |
| 162.159.137.224 | 80, 443, 8080 | 164 |
| 162.159.130.71 | 80, 443, 8080 | 164 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:2c:65ef:c174:419f:91aa:3a23] | 80, 443, 8080 | 3 |
| [2606:4700:22:9a88:c43f:2d7b:70db:cc07] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:71aa:167a:bdb8:94f5:7e7f] | 80, 443, 8080 | 3 |
| [2606:4700:22:c369:537a:d52a:a4f:275b] | 80, 443, 8080 | 3 |
| [2606:4700:2c:65ef:c174:419f:91aa:3a23] | 80, 443, 8080 | 3 |
| [2606:4700:22:9a88:c43f:2d7b:70db:cc07] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:71aa:167a:bdb8:94f5:7e7f] | 80, 443, 8080 | 3 |
| [2606:4700:22:c369:537a:d52a:a4f:275b] | 80, 443, 8080 | 3 |
| [2606:4700:2c:65ef:c174:419f:91aa:3a23] | 80, 443, 8080 | 3 |
| [2606:4700:22:9a88:c43f:2d7b:70db:cc07] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:71aa:167a:bdb8:94f5:7e7f] | 80, 443, 8080 | 3 |
| [2606:4700:22:c369:537a:d52a:a4f:275b] | 80, 443, 8080 | 3 |
| [2606:4700:2c:e0e1:3cfe:43bb:a94a:e845] | 80, 443, 8080 | 13 |
| [2606:4700:2c:e0e1:3cfe:43bb:a94a:e845] | 80, 443, 8080 | 13 |
| [2606:4700:2c:e0e1:3cfe:43bb:a94a:e845] | 80, 443, 8080 | 13 |

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
