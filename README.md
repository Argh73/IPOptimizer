# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-01 03:01:32 +0330

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
| 198.41.208.40 | 80, 443, 8080 | 46 |
| 198.41.208.40 | 80, 443, 8080 | 46 |
| 198.41.208.117 | 80, 443, 8080 | 49 |
| 198.41.208.117 | 80, 443, 8080 | 49 |
| 198.41.209.3 | 80, 443, 8080 | 51 |
| 198.41.209.3 | 80, 443, 8080 | 51 |
| 198.41.208.87 | 80, 443, 8080 | 57 |
| 198.41.208.87 | 80, 443, 8080 | 57 |
| 198.41.208.255 | 80, 443, 8080 | 70 |
| 198.41.208.255 | 80, 443, 8080 | 70 |
| 198.41.222.193 | 80, 443, 8080 | 78 |
| 104.17.115.92 | 80, 443, 8080 | 139 |
| 104.17.58.98 | 80, 443, 8080 | 139 |
| 104.19.75.223 | 80, 443, 8080 | 139 |
| 104.16.210.200 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a68:f837:ca87:7efc:5a76:9b7b] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:aae8:d463:5602:8f6a:76c7] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:110d:7eab:cd04:fd4b:8c46] | 80, 443, 8080 | 3 |
| [2606:4700:8d73:6cfa:6e8a:6a8:62db:8a16] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f837:ca87:7efc:5a76:9b7b] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:aae8:d463:5602:8f6a:76c7] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:110d:7eab:cd04:fd4b:8c46] | 80, 443, 8080 | 3 |
| [2606:4700:8d73:6cfa:6e8a:6a8:62db:8a16] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f837:ca87:7efc:5a76:9b7b] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:aae8:d463:5602:8f6a:76c7] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:110d:7eab:cd04:fd4b:8c46] | 80, 443, 8080 | 3 |
| [2606:4700:8d73:6cfa:6e8a:6a8:62db:8a16] | 80, 443, 8080 | 3 |
| [2606:4700:3033:9633:937b:6af9:8418:ee5f] | 80, 443, 8080 | 13 |
| [2606:4700:3033:9633:937b:6af9:8418:ee5f] | 80, 443, 8080 | 13 |
| [2606:4700:3033:9633:937b:6af9:8418:ee5f] | 80, 443, 8080 | 13 |

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
