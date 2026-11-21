# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-21 05:08:24 +0330

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
| 104.16.185.79 | 80, 443, 8080 | 145 |
| 162.159.160.254 | 80, 443, 8080 | 148 |
| 162.159.160.216 | 80, 443, 8080 | 148 |
| 162.159.160.254 | 80, 443, 8080 | 148 |
| 162.159.160.216 | 80, 443, 8080 | 148 |
| 104.19.71.79 | 80, 443, 8080 | 150 |
| 162.159.160.36 | 80, 443, 8080 | 155 |
| 162.159.160.247 | 80, 443, 8080 | 155 |
| 162.159.160.36 | 80, 443, 8080 | 155 |
| 162.159.160.247 | 80, 443, 8080 | 155 |
| 104.24.193.63 | 80, 443, 8080 | 156 |
| 104.25.187.165 | 80, 443, 8080 | 160 |
| 104.27.41.233 | 80, 443, 8080 | 165 |
| 162.159.135.248 | 80, 443, 8080 | 167 |
| 162.159.135.248 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:99e6:5bd9:1791:9d:1406:fd6c] | 80, 443, 8080 | 3 |
| [2606:4700:19:e2dc:f751:84ea:675a:10f5] | 80, 443, 8080 | 3 |
| [2606:4700:3007:3302:94a:675d:75a6:75bf] | 80, 443, 8080 | 3 |
| [2606:4700:99e6:5bd9:1791:9d:1406:fd6c] | 80, 443, 8080 | 3 |
| [2606:4700:19:e2dc:f751:84ea:675a:10f5] | 80, 443, 8080 | 3 |
| [2606:4700:3007:3302:94a:675d:75a6:75bf] | 80, 443, 8080 | 3 |
| [2606:4700:99e6:5bd9:1791:9d:1406:fd6c] | 80, 443, 8080 | 3 |
| [2606:4700:19:e2dc:f751:84ea:675a:10f5] | 80, 443, 8080 | 3 |
| [2606:4700:3007:3302:94a:675d:75a6:75bf] | 80, 443, 8080 | 3 |
| [2606:4700:3007:1c06:b3d5:798b:e29f:ddd2] | 80, 443, 8080 | 13 |
| [2606:4700:3007:1c06:b3d5:798b:e29f:ddd2] | 80, 443, 8080 | 13 |
| [2606:4700:3007:1c06:b3d5:798b:e29f:ddd2] | 80, 443, 8080 | 13 |
| [2606:4700:83b8:ef32:7cfd:aaf8:42f6:710a] | 80, 443, 8080 | 174 |
| [2606:4700:83b8:ef32:7cfd:aaf8:42f6:710a] | 80, 443, 8080 | 174 |
| [2606:4700:83b8:ef32:7cfd:aaf8:42f6:710a] | 80, 443, 8080 | 174 |

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
