# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-11 11:49:24 +0330

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
| 198.41.209.192 | 80, 443, 8080 | 53 |
| 198.41.209.81 | 80, 443, 8080 | 53 |
| 198.41.209.192 | 80, 443, 8080 | 53 |
| 198.41.209.81 | 80, 443, 8080 | 53 |
| 198.41.208.46 | 80, 443, 8080 | 54 |
| 198.41.209.251 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.208.46 | 80, 443, 8080 | 54 |
| 198.41.209.251 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.211.35 | 80, 443, 8080 | 70 |
| 104.17.208.240 | 80, 443, 8080 | 155 |
| 172.67.175.16 | 80, 443, 8080 | 157 |
| 104.21.36.197 | 80, 443, 8080 | 162 |
| 104.21.105.122 | 80, 443, 8080 | 164 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d7c:79bf:ec03:6a07:9572:6d53] | 80, 443, 8080 | 0 |
| [2606:4700:9b02:7f36:ca4a:c822:ae79:7425] | 80, 443, 8080 | 0 |
| [2606:4700:8d7c:79bf:ec03:6a07:9572:6d53] | 80, 443, 8080 | 0 |
| [2606:4700:9b02:7f36:ca4a:c822:ae79:7425] | 80, 443, 8080 | 0 |
| [2606:4700:8d7c:79bf:ec03:6a07:9572:6d53] | 80, 443, 8080 | 0 |
| [2606:4700:9b02:7f36:ca4a:c822:ae79:7425] | 80, 443, 8080 | 0 |
| [2606:4700:8d7c:6a3c:6e2d:6fe:6c63:c00c] | 80, 443, 8080 | 1 |
| [2606:4700:8d96:83ab:b01c:9189:3ab5:1123] | 80, 443, 8080 | 1 |
| [2606:4700:90da:92b1:8d85:4a58:467f:1d03] | 80, 443, 8080 | 1 |
| [2606:4700:8d7c:6a3c:6e2d:6fe:6c63:c00c] | 80, 443, 8080 | 1 |
| [2606:4700:8d96:83ab:b01c:9189:3ab5:1123] | 80, 443, 8080 | 1 |
| [2606:4700:90da:92b1:8d85:4a58:467f:1d03] | 80, 443, 8080 | 1 |
| [2606:4700:8d7c:6a3c:6e2d:6fe:6c63:c00c] | 80, 443, 8080 | 1 |
| [2606:4700:8d96:83ab:b01c:9189:3ab5:1123] | 80, 443, 8080 | 1 |
| [2606:4700:90da:92b1:8d85:4a58:467f:1d03] | 80, 443, 8080 | 1 |

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
