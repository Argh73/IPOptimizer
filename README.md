# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-18 11:50:04 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 49 |
| 198.41.209.186 | 80, 443, 8080 | 49 |
| 198.41.209.165 | 80, 443, 8080 | 50 |
| 198.41.208.41 | 80, 443, 8080 | 50 |
| 198.41.209.165 | 80, 443, 8080 | 50 |
| 198.41.208.41 | 80, 443, 8080 | 50 |
| 198.41.209.212 | 80, 443, 8080 | 53 |
| 198.41.209.212 | 80, 443, 8080 | 53 |
| 198.41.208.167 | 80, 443, 8080 | 54 |
| 198.41.208.167 | 80, 443, 8080 | 54 |
| 198.41.223.93 | 80, 443, 8080 | 76 |
| 104.16.232.203 | 80, 443, 8080 | 144 |
| 104.19.207.100 | 80, 443, 8080 | 145 |
| 104.19.94.144 | 80, 443, 8080 | 156 |
| 104.24.51.168 | 80, 443, 8080 | 161 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:130:23d5:ba9f:10fa:36dc:8d56] | 80, 443, 8080 | 3 |
| [2606:4700:13a:d03a:f41b:da8a:4457:7f11] | 80, 443, 8080 | 3 |
| [2606:4700:d0:76b4:44ef:8359:d0c8:5950] | 80, 443, 8080 | 3 |
| [2606:4700:130:920d:9bbf:228b:9d48:9b3c] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:d527:b05f:997b:dca4:b90e] | 80, 443, 8080 | 3 |
| [2606:4700:130:23d5:ba9f:10fa:36dc:8d56] | 80, 443, 8080 | 3 |
| [2606:4700:13a:d03a:f41b:da8a:4457:7f11] | 80, 443, 8080 | 3 |
| [2606:4700:d0:76b4:44ef:8359:d0c8:5950] | 80, 443, 8080 | 3 |
| [2606:4700:130:920d:9bbf:228b:9d48:9b3c] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:d527:b05f:997b:dca4:b90e] | 80, 443, 8080 | 3 |
| [2606:4700:130:23d5:ba9f:10fa:36dc:8d56] | 80, 443, 8080 | 3 |
| [2606:4700:13a:d03a:f41b:da8a:4457:7f11] | 80, 443, 8080 | 3 |
| [2606:4700:d0:76b4:44ef:8359:d0c8:5950] | 80, 443, 8080 | 3 |
| [2606:4700:130:920d:9bbf:228b:9d48:9b3c] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:d527:b05f:997b:dca4:b90e] | 80, 443, 8080 | 3 |

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
