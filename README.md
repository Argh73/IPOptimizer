# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-20 10:52:41 +0330

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
| 104.17.196.242 | 80, 443, 8080 | 141 |
| 104.17.209.38 | 80, 443, 8080 | 142 |
| 104.17.18.118 | 80, 443, 8080 | 142 |
| 104.19.117.52 | 80, 443, 8080 | 142 |
| 104.17.194.184 | 80, 443, 8080 | 143 |
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
| [2606:4700:3010:f820:204:a19c:2656:8f58] | 80, 443, 8080 | 0 |
| [2606:4700:3010:8e76:bd:de66:e6d0:e2f5] | 80, 443, 8080 | 0 |
| [2606:4700:3010:f820:204:a19c:2656:8f58] | 80, 443, 8080 | 0 |
| [2606:4700:3010:8e76:bd:de66:e6d0:e2f5] | 80, 443, 8080 | 0 |
| [2606:4700:3010:f820:204:a19c:2656:8f58] | 80, 443, 8080 | 0 |
| [2606:4700:3010:8e76:bd:de66:e6d0:e2f5] | 80, 443, 8080 | 0 |
| [2606:4700:101:6ebe:465:fc7a:ec35:a12] | 80, 443, 8080 | 1 |
| [2606:4700:13f:fe:78c6:93ad:8458:5f89] | 80, 443, 8080 | 1 |
| [2606:4700:101:26ac:fe33:fe37:4d53:d8b6] | 80, 443, 8080 | 1 |
| [2606:4700:101:6ebe:465:fc7a:ec35:a12] | 80, 443, 8080 | 1 |
| [2606:4700:13f:fe:78c6:93ad:8458:5f89] | 80, 443, 8080 | 1 |
| [2606:4700:101:26ac:fe33:fe37:4d53:d8b6] | 80, 443, 8080 | 1 |
| [2606:4700:101:6ebe:465:fc7a:ec35:a12] | 80, 443, 8080 | 1 |
| [2606:4700:13f:fe:78c6:93ad:8458:5f89] | 80, 443, 8080 | 1 |
| [2606:4700:101:26ac:fe33:fe37:4d53:d8b6] | 80, 443, 8080 | 1 |

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
