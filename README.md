# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-15 15:29:09 +0330

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
| 198.41.208.23 | 80, 443, 8080 | 50 |
| 198.41.208.23 | 80, 443, 8080 | 50 |
| 198.41.209.92 | 80, 443, 8080 | 54 |
| 198.41.209.92 | 80, 443, 8080 | 54 |
| 198.41.208.175 | 80, 443, 8080 | 58 |
| 198.41.208.175 | 80, 443, 8080 | 58 |
| 198.41.222.50 | 80, 443, 8080 | 69 |
| 198.41.209.207 | 80, 443, 8080 | 71 |
| 198.41.209.207 | 80, 443, 8080 | 71 |
| 162.159.46.202 | 80, 443, 8080 | 91 |
| 198.41.208.172 | 80, 443, 8080 | 94 |
| 198.41.208.172 | 80, 443, 8080 | 94 |
| 172.64.93.51 | 80, 443, 8080 | 139 |
| 104.17.59.217 | 80, 443, 8080 | 142 |
| 172.64.79.113 | 80, 443, 8080 | 144 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de0:82dc:e6fe:834d:ce6c:71ca] | 80, 443, 8080 | 3 |
| [2606:4700:9aef:3697:49b5:90ea:2812:6199] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:93f1:cb5a:5fdb:27a7:f997] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:c5f2:ae6f:27b5:101c:1f68] | 80, 443, 8080 | 3 |
| [2606:4700:8de0:82dc:e6fe:834d:ce6c:71ca] | 80, 443, 8080 | 3 |
| [2606:4700:9aef:3697:49b5:90ea:2812:6199] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:93f1:cb5a:5fdb:27a7:f997] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:c5f2:ae6f:27b5:101c:1f68] | 80, 443, 8080 | 3 |
| [2606:4700:8de0:82dc:e6fe:834d:ce6c:71ca] | 80, 443, 8080 | 3 |
| [2606:4700:9aef:3697:49b5:90ea:2812:6199] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:93f1:cb5a:5fdb:27a7:f997] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:c5f2:ae6f:27b5:101c:1f68] | 80, 443, 8080 | 3 |
| [2606:4700:90d7:867c:1f61:7e9b:a7c1:7962] | 80, 443, 8080 | 6 |
| [2606:4700:90d7:867c:1f61:7e9b:a7c1:7962] | 80, 443, 8080 | 6 |
| [2606:4700:90d7:867c:1f61:7e9b:a7c1:7962] | 80, 443, 8080 | 6 |

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
