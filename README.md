# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-17 00:16:56 +0330

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
| 198.41.209.35 | 80, 443, 8080 | 53 |
| 198.41.209.35 | 80, 443, 8080 | 53 |
| 198.41.208.67 | 80, 443, 8080 | 54 |
| 198.41.208.67 | 80, 443, 8080 | 54 |
| 198.41.209.0 | 80, 443, 8080 | 56 |
| 198.41.208.220 | 80, 443, 8080 | 56 |
| 198.41.209.0 | 80, 443, 8080 | 56 |
| 198.41.208.220 | 80, 443, 8080 | 56 |
| 104.19.183.69 | 80, 443, 8080 | 138 |
| 104.19.98.198 | 80, 443, 8080 | 138 |
| 104.19.193.71 | 80, 443, 8080 | 138 |
| 104.18.166.12 | 80, 443, 8080 | 139 |
| 104.18.106.96 | 80, 443, 8080 | 139 |
| 172.64.75.153 | 80, 443, 8080 | 180 |
| 172.64.75.153 | 80, 443, 8080 | 180 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90dd:89b8:e56f:b33:e39:bd3a] | 80, 443, 8080 | 3 |
| [2606:4700:3025:43c0:7ecf:937f:b7ba:dfa4] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:ef4e:af2c:84fc:8ed1:271a] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:6012:7ae8:2008:ee6e:3a1d] | 80, 443, 8080 | 3 |
| [2606:4700:90dd:89b8:e56f:b33:e39:bd3a] | 80, 443, 8080 | 3 |
| [2606:4700:3025:43c0:7ecf:937f:b7ba:dfa4] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:ef4e:af2c:84fc:8ed1:271a] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:6012:7ae8:2008:ee6e:3a1d] | 80, 443, 8080 | 3 |
| [2606:4700:90dd:89b8:e56f:b33:e39:bd3a] | 80, 443, 8080 | 3 |
| [2606:4700:3025:43c0:7ecf:937f:b7ba:dfa4] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:ef4e:af2c:84fc:8ed1:271a] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:6012:7ae8:2008:ee6e:3a1d] | 80, 443, 8080 | 3 |
| [2606:4700:131:a595:a3f5:fd25:dabb:9e4c] | 80, 443, 8080 | 13 |
| [2606:4700:131:a595:a3f5:fd25:dabb:9e4c] | 80, 443, 8080 | 13 |
| [2606:4700:131:a595:a3f5:fd25:dabb:9e4c] | 80, 443, 8080 | 13 |

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
