# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-21 00:25:40 +0330

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
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 104.19.127.193 | 80, 443, 8080 | 138 |
| 104.19.12.93 | 80, 443, 8080 | 138 |
| 104.17.236.138 | 80, 443, 8080 | 139 |
| 104.16.24.18 | 80, 443, 8080 | 139 |
| 104.16.10.185 | 80, 443, 8080 | 139 |
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
| [2606:4700:9c63:25fd:f294:e640:a232:cbc4] | 80, 443, 8080 | 0 |
| [2606:4700:21:8a8f:d5a9:526d:b41b:f85c] | 80, 443, 8080 | 0 |
| [2606:4700:9c63:25fd:f294:e640:a232:cbc4] | 80, 443, 8080 | 0 |
| [2606:4700:21:8a8f:d5a9:526d:b41b:f85c] | 80, 443, 8080 | 0 |
| [2606:4700:9c63:25fd:f294:e640:a232:cbc4] | 80, 443, 8080 | 0 |
| [2606:4700:21:8a8f:d5a9:526d:b41b:f85c] | 80, 443, 8080 | 0 |
| [2606:4700:9b00:4987:ecb7:f8f:eb63:6994] | 80, 443, 8080 | 1 |
| [2606:4700:99ed:8c6a:6b95:f426:d7fa:3097] | 80, 443, 8080 | 1 |
| [2606:4700:9b00:7cff:b56:d758:5a8d:f8c9] | 80, 443, 8080 | 1 |
| [2606:4700:9b00:4987:ecb7:f8f:eb63:6994] | 80, 443, 8080 | 1 |
| [2606:4700:99ed:8c6a:6b95:f426:d7fa:3097] | 80, 443, 8080 | 1 |
| [2606:4700:9b00:7cff:b56:d758:5a8d:f8c9] | 80, 443, 8080 | 1 |
| [2606:4700:9b00:4987:ecb7:f8f:eb63:6994] | 80, 443, 8080 | 1 |
| [2606:4700:99ed:8c6a:6b95:f426:d7fa:3097] | 80, 443, 8080 | 1 |
| [2606:4700:9b00:7cff:b56:d758:5a8d:f8c9] | 80, 443, 8080 | 1 |

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
