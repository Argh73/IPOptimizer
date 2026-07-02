# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-03 01:13:07 +0330

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
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.208.67 | 80, 443, 8080 | 56 |
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 198.41.208.46 | 80, 443, 8080 | 56 |
| 198.41.208.67 | 80, 443, 8080 | 56 |
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 198.41.208.46 | 80, 443, 8080 | 56 |
| 104.17.107.176 | 80, 443, 8080 | 129 |
| 104.17.18.64 | 80, 443, 8080 | 130 |
| 141.101.120.163 | 80, 443, 8080 | 130 |
| 104.18.135.44 | 80, 443, 8080 | 130 |
| 104.16.93.239 | 80, 443, 8080 | 130 |
| 172.67.116.63 | 80, 443, 8080 | 184 |
| 172.67.116.63 | 80, 443, 8080 | 184 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:2:ad11:846d:b5ea:e201:bbc2] | 80, 443, 8080 | 0 |
| [2606:4700:2:93bc:5d40:125f:eb3d:bb67] | 80, 443, 8080 | 0 |
| [2606:4700:2:ad11:846d:b5ea:e201:bbc2] | 80, 443, 8080 | 0 |
| [2606:4700:2:93bc:5d40:125f:eb3d:bb67] | 80, 443, 8080 | 0 |
| [2606:4700:2:ad11:846d:b5ea:e201:bbc2] | 80, 443, 8080 | 0 |
| [2606:4700:2:93bc:5d40:125f:eb3d:bb67] | 80, 443, 8080 | 0 |
| [2606:4700:9c63:d9f8:f5b9:67f7:b73b:a53b] | 80, 443, 8080 | 1 |
| [2606:4700:90dd:49ff:16e6:d8e9:95b5:9613] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:d9f8:f5b9:67f7:b73b:a53b] | 80, 443, 8080 | 1 |
| [2606:4700:90dd:49ff:16e6:d8e9:95b5:9613] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:d9f8:f5b9:67f7:b73b:a53b] | 80, 443, 8080 | 1 |
| [2606:4700:90dd:49ff:16e6:d8e9:95b5:9613] | 80, 443, 8080 | 1 |
| [2606:4700:8ca3:d73c:65ef:b318:db67:4960] | 80, 443, 8080 | 123 |
| [2606:4700:8ca3:d73c:65ef:b318:db67:4960] | 80, 443, 8080 | 123 |
| [2606:4700:8ca3:d73c:65ef:b318:db67:4960] | 80, 443, 8080 | 123 |

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
