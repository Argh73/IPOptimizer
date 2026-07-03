# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-03 13:12:27 +0330

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
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 162.159.36.17 | 80, 443, 8080 | 79 |
| 162.159.36.17 | 80, 443, 8080 | 79 |
| 162.159.36.17 | 80, 443, 8080 | 79 |
| 104.19.59.75 | 80, 443, 8080 | 130 |
| 104.19.59.75 | 80, 443, 8080 | 130 |
| 104.19.59.75 | 80, 443, 8080 | 130 |
| 104.18.88.0 | 80, 443, 8080 | 132 |
| 104.18.88.0 | 80, 443, 8080 | 132 |
| 104.18.88.0 | 80, 443, 8080 | 132 |
| 104.16.202.162 | 80, 443, 8080 | 133 |
| 104.16.202.162 | 80, 443, 8080 | 133 |
| 104.16.202.162 | 80, 443, 8080 | 133 |
| 104.18.95.46 | 80, 443, 8080 | 134 |
| 104.18.95.46 | 80, 443, 8080 | 134 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:1b:b2ef:e628:48ab:51dc:12ba] | 80, 443, 8080 | 0 |
| [2606:4700:91ba:9e39:e7e0:71da:2189:e574] | 80, 443, 8080 | 0 |
| [2606:4700:91b6:6fd9:aadd:28b9:a487:c57c] | 80, 443, 8080 | 0 |
| [2606:4700:91ba:31d7:b44c:80dd:8a79:37f6] | 80, 443, 8080 | 0 |
| [2606:4700:1b:b2ef:e628:48ab:51dc:12ba] | 80, 443, 8080 | 0 |
| [2606:4700:91ba:9e39:e7e0:71da:2189:e574] | 80, 443, 8080 | 0 |
| [2606:4700:91b6:6fd9:aadd:28b9:a487:c57c] | 80, 443, 8080 | 0 |
| [2606:4700:91ba:31d7:b44c:80dd:8a79:37f6] | 80, 443, 8080 | 0 |
| [2606:4700:1b:b2ef:e628:48ab:51dc:12ba] | 80, 443, 8080 | 0 |
| [2606:4700:91ba:9e39:e7e0:71da:2189:e574] | 80, 443, 8080 | 0 |
| [2606:4700:91b6:6fd9:aadd:28b9:a487:c57c] | 80, 443, 8080 | 0 |
| [2606:4700:91ba:31d7:b44c:80dd:8a79:37f6] | 80, 443, 8080 | 0 |
| [2606:4700:90df:9f31:6185:aa90:d741:bf2d] | 80, 443, 8080 | 1 |
| [2606:4700:90df:9f31:6185:aa90:d741:bf2d] | 80, 443, 8080 | 1 |
| [2606:4700:90df:9f31:6185:aa90:d741:bf2d] | 80, 443, 8080 | 1 |

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
