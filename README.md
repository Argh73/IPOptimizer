# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-25 01:06:41 +0330

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
| 104.17.166.168 | 80, 443, 8080 | 139 |
| 104.19.151.147 | 80, 443, 8080 | 139 |
| 104.17.6.3 | 80, 443, 8080 | 139 |
| 104.17.100.243 | 80, 443, 8080 | 140 |
| 104.19.244.235 | 80, 443, 8080 | 149 |
| 141.101.121.162 | 80, 443, 8080 | 179 |
| 141.101.121.162 | 80, 443, 8080 | 179 |
| 172.64.86.28 | 80, 443, 8080 | 180 |
| 172.64.82.234 | 80, 443, 8080 | 180 |
| 172.67.86.163 | 80, 443, 8080 | 180 |
| 172.64.86.28 | 80, 443, 8080 | 180 |
| 172.64.82.234 | 80, 443, 8080 | 180 |
| 172.67.86.163 | 80, 443, 8080 | 180 |
| 172.67.180.201 | 80, 443, 8080 | 182 |
| 172.67.180.201 | 80, 443, 8080 | 182 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:130:3c3:3f9f:72dc:2dde:f530] | 80, 443, 8080 | 0 |
| [2606:4700:8cac:76e7:a2af:5c98:3f8:6019] | 80, 443, 8080 | 0 |
| [2606:4700:130:3c3:3f9f:72dc:2dde:f530] | 80, 443, 8080 | 0 |
| [2606:4700:8cac:76e7:a2af:5c98:3f8:6019] | 80, 443, 8080 | 0 |
| [2606:4700:130:3c3:3f9f:72dc:2dde:f530] | 80, 443, 8080 | 0 |
| [2606:4700:8cac:76e7:a2af:5c98:3f8:6019] | 80, 443, 8080 | 0 |
| [2606:4700:9645:40ec:103d:f0fe:bd39:92c4] | 80, 443, 8080 | 1 |
| [2606:4700:19:fb91:3fcf:c4e9:3476:499e] | 80, 443, 8080 | 1 |
| [2606:4700:976c:afb0:9245:f468:4785:e880] | 80, 443, 8080 | 1 |
| [2606:4700:9645:40ec:103d:f0fe:bd39:92c4] | 80, 443, 8080 | 1 |
| [2606:4700:19:fb91:3fcf:c4e9:3476:499e] | 80, 443, 8080 | 1 |
| [2606:4700:976c:afb0:9245:f468:4785:e880] | 80, 443, 8080 | 1 |
| [2606:4700:9645:40ec:103d:f0fe:bd39:92c4] | 80, 443, 8080 | 1 |
| [2606:4700:19:fb91:3fcf:c4e9:3476:499e] | 80, 443, 8080 | 1 |
| [2606:4700:976c:afb0:9245:f468:4785:e880] | 80, 443, 8080 | 1 |

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
