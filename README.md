# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-10 11:43:11 +0330

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
| 198.41.209.37 | 80, 443, 8080 | 57 |
| 198.41.209.37 | 80, 443, 8080 | 57 |
| 198.41.209.6 | 80, 443, 8080 | 140 |
| 198.41.209.6 | 80, 443, 8080 | 140 |
| 104.17.27.127 | 80, 443, 8080 | 142 |
| 104.16.226.248 | 80, 443, 8080 | 142 |
| 104.18.149.127 | 80, 443, 8080 | 142 |
| 104.19.45.173 | 80, 443, 8080 | 142 |
| 104.16.201.239 | 80, 443, 8080 | 143 |
| 198.41.209.62 | 80, 443, 8080 | 156 |
| 198.41.209.62 | 80, 443, 8080 | 156 |
| 198.41.208.67 | 80, 443, 8080 | 160 |
| 198.41.208.67 | 80, 443, 8080 | 160 |
| 198.41.208.43 | 80, 443, 8080 | 166 |
| 198.41.208.43 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:d0:183e:911d:1c38:60b8:c264] | 80, 443, 8080 | 0 |
| [2606:4700:54:58b9:b092:551c:dba5:3a27] | 80, 443, 8080 | 0 |
| [2606:4700:d0:183e:911d:1c38:60b8:c264] | 80, 443, 8080 | 0 |
| [2606:4700:54:58b9:b092:551c:dba5:3a27] | 80, 443, 8080 | 0 |
| [2606:4700:d0:183e:911d:1c38:60b8:c264] | 80, 443, 8080 | 0 |
| [2606:4700:54:58b9:b092:551c:dba5:3a27] | 80, 443, 8080 | 0 |
| [2606:4700:54:687c:db9c:80cb:3c8c:f5ac] | 80, 443, 8080 | 1 |
| [2606:4700:54:687c:db9c:80cb:3c8c:f5ac] | 80, 443, 8080 | 1 |
| [2606:4700:54:687c:db9c:80cb:3c8c:f5ac] | 80, 443, 8080 | 1 |
| [2606:4700:83b4:e735:4ea1:3c67:1b49:4b19] | 80, 443, 8080 | 161 |
| [2606:4700:83b9:e019:d855:429d:c2d9:c19b] | 80, 443, 8080 | 161 |
| [2606:4700:83b4:e735:4ea1:3c67:1b49:4b19] | 80, 443, 8080 | 161 |
| [2606:4700:83b9:e019:d855:429d:c2d9:c19b] | 80, 443, 8080 | 161 |
| [2606:4700:83b4:e735:4ea1:3c67:1b49:4b19] | 80, 443, 8080 | 161 |
| [2606:4700:83b9:e019:d855:429d:c2d9:c19b] | 80, 443, 8080 | 161 |

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
