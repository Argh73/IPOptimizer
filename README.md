# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-23 02:37:49 +0330

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
| 198.41.208.120 | 80, 443, 8080 | 50 |
| 198.41.208.120 | 80, 443, 8080 | 50 |
| 198.41.209.240 | 80, 443, 8080 | 51 |
| 198.41.208.118 | 80, 443, 8080 | 51 |
| 198.41.209.240 | 80, 443, 8080 | 51 |
| 198.41.208.118 | 80, 443, 8080 | 51 |
| 198.41.208.81 | 80, 443, 8080 | 52 |
| 198.41.208.81 | 80, 443, 8080 | 52 |
| 198.41.208.41 | 80, 443, 8080 | 57 |
| 198.41.208.41 | 80, 443, 8080 | 57 |
| 162.159.46.137 | 80, 443, 8080 | 70 |
| 104.19.249.66 | 80, 443, 8080 | 139 |
| 104.18.86.163 | 80, 443, 8080 | 139 |
| 104.16.97.247 | 80, 443, 8080 | 139 |
| 104.16.107.42 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:976c:da01:c8e8:8bc8:899e:9544] | 80, 443, 8080 | 3 |
| [2606:4700:839f:8a28:2ab8:faec:d07a:930b] | 80, 443, 8080 | 3 |
| [2606:4700:839f:f73f:35a1:8ba7:462a:d416] | 80, 443, 8080 | 3 |
| [2606:4700:976c:da01:c8e8:8bc8:899e:9544] | 80, 443, 8080 | 3 |
| [2606:4700:839f:8a28:2ab8:faec:d07a:930b] | 80, 443, 8080 | 3 |
| [2606:4700:839f:f73f:35a1:8ba7:462a:d416] | 80, 443, 8080 | 3 |
| [2606:4700:976c:da01:c8e8:8bc8:899e:9544] | 80, 443, 8080 | 3 |
| [2606:4700:839f:8a28:2ab8:faec:d07a:930b] | 80, 443, 8080 | 3 |
| [2606:4700:839f:f73f:35a1:8ba7:462a:d416] | 80, 443, 8080 | 3 |
| [2606:4700:4700:a84c:3c02:e10f:98f6:291a] | 80, 443, 8080 | 13 |
| [2606:4700:4700:6941:c953:f763:3ec1:2ffa] | 80, 443, 8080 | 13 |
| [2606:4700:4700:a84c:3c02:e10f:98f6:291a] | 80, 443, 8080 | 13 |
| [2606:4700:4700:6941:c953:f763:3ec1:2ffa] | 80, 443, 8080 | 13 |
| [2606:4700:4700:a84c:3c02:e10f:98f6:291a] | 80, 443, 8080 | 13 |
| [2606:4700:4700:6941:c953:f763:3ec1:2ffa] | 80, 443, 8080 | 13 |

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
