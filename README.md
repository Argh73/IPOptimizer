# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-28 02:44:19 +0330

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
| 198.41.208.3 | 80, 443, 8080 | 51 |
| 198.41.208.3 | 80, 443, 8080 | 51 |
| 198.41.209.21 | 80, 443, 8080 | 53 |
| 198.41.209.21 | 80, 443, 8080 | 53 |
| 198.41.209.18 | 80, 443, 8080 | 54 |
| 198.41.209.18 | 80, 443, 8080 | 54 |
| 198.41.209.13 | 80, 443, 8080 | 59 |
| 198.41.209.13 | 80, 443, 8080 | 59 |
| 198.41.223.98 | 80, 443, 8080 | 64 |
| 198.41.208.62 | 80, 443, 8080 | 101 |
| 198.41.208.62 | 80, 443, 8080 | 101 |
| 104.18.253.116 | 80, 443, 8080 | 139 |
| 104.18.182.245 | 80, 443, 8080 | 139 |
| 104.17.128.58 | 80, 443, 8080 | 139 |
| 104.19.240.87 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:4:be6e:a32:a737:e905:fd1] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:b532:be96:e93b:6cb2:805a] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:55eb:2cdb:7ce3:9ca4:fe1d] | 80, 443, 8080 | 3 |
| [2606:4700:310c:8d0f:d180:2518:71e7:e04e] | 80, 443, 8080 | 3 |
| [2606:4700:4:be6e:a32:a737:e905:fd1] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:b532:be96:e93b:6cb2:805a] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:55eb:2cdb:7ce3:9ca4:fe1d] | 80, 443, 8080 | 3 |
| [2606:4700:310c:8d0f:d180:2518:71e7:e04e] | 80, 443, 8080 | 3 |
| [2606:4700:4:be6e:a32:a737:e905:fd1] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:b532:be96:e93b:6cb2:805a] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:55eb:2cdb:7ce3:9ca4:fe1d] | 80, 443, 8080 | 3 |
| [2606:4700:310c:8d0f:d180:2518:71e7:e04e] | 80, 443, 8080 | 3 |
| [2606:4700:2c:d07f:751b:7d64:cc1a:86d3] | 80, 443, 8080 | 13 |
| [2606:4700:2c:d07f:751b:7d64:cc1a:86d3] | 80, 443, 8080 | 13 |
| [2606:4700:2c:d07f:751b:7d64:cc1a:86d3] | 80, 443, 8080 | 13 |

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
