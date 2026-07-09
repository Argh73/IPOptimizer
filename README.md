# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-10 01:26:13 +0330

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
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.209.145 | 80, 443, 8080 | 59 |
| 198.41.209.145 | 80, 443, 8080 | 59 |
| 198.41.223.14 | 80, 443, 8080 | 75 |
| 104.19.38.127 | 80, 443, 8080 | 139 |
| 104.18.12.185 | 80, 443, 8080 | 139 |
| 104.18.166.247 | 80, 443, 8080 | 139 |
| 104.19.25.19 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a66:45ee:81b8:e9bf:15b7:e38d] | 80, 443, 8080 | 0 |
| [2606:4700:9a66:45ee:81b8:e9bf:15b7:e38d] | 80, 443, 8080 | 0 |
| [2606:4700:9a66:45ee:81b8:e9bf:15b7:e38d] | 80, 443, 8080 | 0 |
| [2606:4700:9648:adf7:1fb1:9823:94f1:e567] | 80, 443, 8080 | 1 |
| [2606:4700:9a98:6c18:439c:8d64:8186:adaa] | 80, 443, 8080 | 1 |
| [2606:4700:9b0c:ca8f:75ed:e759:e2c7:b3ed] | 80, 443, 8080 | 1 |
| [2606:4700:9a98:9fb0:b25f:ca8a:98b0:af52] | 80, 443, 8080 | 1 |
| [2606:4700:9648:adf7:1fb1:9823:94f1:e567] | 80, 443, 8080 | 1 |
| [2606:4700:9a98:6c18:439c:8d64:8186:adaa] | 80, 443, 8080 | 1 |
| [2606:4700:9b0c:ca8f:75ed:e759:e2c7:b3ed] | 80, 443, 8080 | 1 |
| [2606:4700:9a98:9fb0:b25f:ca8a:98b0:af52] | 80, 443, 8080 | 1 |
| [2606:4700:9648:adf7:1fb1:9823:94f1:e567] | 80, 443, 8080 | 1 |
| [2606:4700:9a98:6c18:439c:8d64:8186:adaa] | 80, 443, 8080 | 1 |
| [2606:4700:9b0c:ca8f:75ed:e759:e2c7:b3ed] | 80, 443, 8080 | 1 |
| [2606:4700:9a98:9fb0:b25f:ca8a:98b0:af52] | 80, 443, 8080 | 1 |

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
