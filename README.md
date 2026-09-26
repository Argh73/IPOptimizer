# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-27 02:33:37 +0330

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
| 198.41.209.56 | 80, 443, 8080 | 51 |
| 198.41.209.111 | 80, 443, 8080 | 51 |
| 198.41.209.56 | 80, 443, 8080 | 51 |
| 198.41.209.111 | 80, 443, 8080 | 51 |
| 198.41.209.248 | 80, 443, 8080 | 53 |
| 198.41.209.248 | 80, 443, 8080 | 53 |
| 198.41.208.220 | 80, 443, 8080 | 71 |
| 198.41.208.220 | 80, 443, 8080 | 71 |
| 198.41.211.229 | 80, 443, 8080 | 82 |
| 198.41.208.76 | 80, 443, 8080 | 101 |
| 198.41.208.76 | 80, 443, 8080 | 101 |
| 104.17.126.110 | 80, 443, 8080 | 140 |
| 104.18.83.20 | 80, 443, 8080 | 140 |
| 104.18.243.176 | 80, 443, 8080 | 140 |
| 104.17.91.162 | 80, 443, 8080 | 141 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:839b:a479:5057:d64d:3593:46bb] | 80, 443, 8080 | 3 |
| [2606:4700:839b:9e0b:a847:8f03:192a:4b5f] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d900:de2f:839d:7ab6:450a] | 80, 443, 8080 | 3 |
| [2606:4700:18:62f1:2091:9859:32c:884c] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:2ee8:7e7b:a2dc:aad1:dfdd] | 80, 443, 8080 | 3 |
| [2606:4700:839b:a479:5057:d64d:3593:46bb] | 80, 443, 8080 | 3 |
| [2606:4700:839b:9e0b:a847:8f03:192a:4b5f] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d900:de2f:839d:7ab6:450a] | 80, 443, 8080 | 3 |
| [2606:4700:18:62f1:2091:9859:32c:884c] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:2ee8:7e7b:a2dc:aad1:dfdd] | 80, 443, 8080 | 3 |
| [2606:4700:839b:a479:5057:d64d:3593:46bb] | 80, 443, 8080 | 3 |
| [2606:4700:839b:9e0b:a847:8f03:192a:4b5f] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:d900:de2f:839d:7ab6:450a] | 80, 443, 8080 | 3 |
| [2606:4700:18:62f1:2091:9859:32c:884c] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:2ee8:7e7b:a2dc:aad1:dfdd] | 80, 443, 8080 | 3 |

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
