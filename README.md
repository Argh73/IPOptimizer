# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-08 12:37:09 +0330

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
| 198.41.209.50 | 80, 443, 8080 | 51 |
| 198.41.209.50 | 80, 443, 8080 | 51 |
| 198.41.209.213 | 80, 443, 8080 | 52 |
| 198.41.209.213 | 80, 443, 8080 | 52 |
| 198.41.209.228 | 80, 443, 8080 | 54 |
| 198.41.209.228 | 80, 443, 8080 | 54 |
| 104.18.91.132 | 80, 443, 8080 | 133 |
| 104.17.127.223 | 80, 443, 8080 | 133 |
| 141.101.114.49 | 80, 443, 8080 | 133 |
| 104.19.147.37 | 80, 443, 8080 | 134 |
| 104.18.250.73 | 80, 443, 8080 | 134 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3:370b:3e29:adc7:a91c:aeb9] | 80, 443, 8080 | 0 |
| [2606:4700:3:5f70:41c9:3de:9ad6:5d36] | 80, 443, 8080 | 0 |
| [2606:4700:17:c56a:d25a:1510:56a2:bcf9] | 80, 443, 8080 | 0 |
| [2606:4700:90d1:9883:47c5:8d0e:276c:414b] | 80, 443, 8080 | 0 |
| [2606:4700:3038:5385:b050:6db3:cfb9:639e] | 80, 443, 8080 | 0 |
| [2606:4700:3:370b:3e29:adc7:a91c:aeb9] | 80, 443, 8080 | 0 |
| [2606:4700:3:5f70:41c9:3de:9ad6:5d36] | 80, 443, 8080 | 0 |
| [2606:4700:17:c56a:d25a:1510:56a2:bcf9] | 80, 443, 8080 | 0 |
| [2606:4700:90d1:9883:47c5:8d0e:276c:414b] | 80, 443, 8080 | 0 |
| [2606:4700:3038:5385:b050:6db3:cfb9:639e] | 80, 443, 8080 | 0 |
| [2606:4700:3:370b:3e29:adc7:a91c:aeb9] | 80, 443, 8080 | 0 |
| [2606:4700:3:5f70:41c9:3de:9ad6:5d36] | 80, 443, 8080 | 0 |
| [2606:4700:17:c56a:d25a:1510:56a2:bcf9] | 80, 443, 8080 | 0 |
| [2606:4700:90d1:9883:47c5:8d0e:276c:414b] | 80, 443, 8080 | 0 |
| [2606:4700:3038:5385:b050:6db3:cfb9:639e] | 80, 443, 8080 | 0 |

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
