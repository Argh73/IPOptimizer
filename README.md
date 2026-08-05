# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-05 12:48:38 +0330

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
| 198.41.208.133 | 80, 443, 8080 | 51 |
| 198.41.208.133 | 80, 443, 8080 | 51 |
| 162.159.135.250 | 80, 443, 8080 | 53 |
| 162.159.133.20 | 80, 443, 8080 | 53 |
| 162.159.135.250 | 80, 443, 8080 | 53 |
| 162.159.133.20 | 80, 443, 8080 | 53 |
| 198.41.209.249 | 80, 443, 8080 | 55 |
| 198.41.208.75 | 80, 443, 8080 | 55 |
| 198.41.209.249 | 80, 443, 8080 | 55 |
| 198.41.208.75 | 80, 443, 8080 | 55 |
| 104.16.164.124 | 80, 443, 8080 | 143 |
| 104.19.247.181 | 80, 443, 8080 | 145 |
| 104.17.17.2 | 80, 443, 8080 | 153 |
| 162.159.246.125 | 80, 443, 8080 | 153 |
| 104.18.155.136 | 80, 443, 8080 | 153 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9645:42c8:b658:67a8:16d9:1b13] | 80, 443, 8080 | 0 |
| [2606:4700:8d97:d7af:618b:b2cb:d647:a16b] | 80, 443, 8080 | 0 |
| [2606:4700:21:7efd:4872:5c43:960b:4f05] | 80, 443, 8080 | 0 |
| [2606:4700:8d97:c8f6:7355:fbc2:ff32:9692] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:f00e:cb2f:e39b:7cf7:d953] | 80, 443, 8080 | 0 |
| [2606:4700:9645:42c8:b658:67a8:16d9:1b13] | 80, 443, 8080 | 0 |
| [2606:4700:8d97:d7af:618b:b2cb:d647:a16b] | 80, 443, 8080 | 0 |
| [2606:4700:21:7efd:4872:5c43:960b:4f05] | 80, 443, 8080 | 0 |
| [2606:4700:8d97:c8f6:7355:fbc2:ff32:9692] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:f00e:cb2f:e39b:7cf7:d953] | 80, 443, 8080 | 0 |
| [2606:4700:9645:42c8:b658:67a8:16d9:1b13] | 80, 443, 8080 | 0 |
| [2606:4700:8d97:d7af:618b:b2cb:d647:a16b] | 80, 443, 8080 | 0 |
| [2606:4700:21:7efd:4872:5c43:960b:4f05] | 80, 443, 8080 | 0 |
| [2606:4700:8d97:c8f6:7355:fbc2:ff32:9692] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:f00e:cb2f:e39b:7cf7:d953] | 80, 443, 8080 | 0 |

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
