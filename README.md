# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-29 01:07:19 +0330

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
| 104.16.133.64 | 80, 443, 8080 | 133 |
| 104.17.185.134 | 80, 443, 8080 | 133 |
| 104.16.133.64 | 80, 443, 8080 | 133 |
| 104.17.185.134 | 80, 443, 8080 | 133 |
| 104.16.133.64 | 80, 443, 8080 | 133 |
| 104.17.185.134 | 80, 443, 8080 | 133 |
| 104.19.164.69 | 80, 443, 8080 | 145 |
| 104.19.164.69 | 80, 443, 8080 | 145 |
| 104.19.164.69 | 80, 443, 8080 | 145 |
| 104.18.120.104 | 80, 443, 8080 | 146 |
| 104.18.120.104 | 80, 443, 8080 | 146 |
| 104.18.120.104 | 80, 443, 8080 | 146 |
| 104.19.185.42 | 80, 443, 8080 | 148 |
| 104.19.185.42 | 80, 443, 8080 | 148 |
| 104.19.185.42 | 80, 443, 8080 | 148 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:99e6:84fc:bd92:ad89:3764:1531] | 80, 443, 8080 | 0 |
| [2606:4700:9a64:7143:8bdd:9979:d712:8709] | 80, 443, 8080 | 0 |
| [2606:4700:99e6:84fc:bd92:ad89:3764:1531] | 80, 443, 8080 | 0 |
| [2606:4700:9a64:7143:8bdd:9979:d712:8709] | 80, 443, 8080 | 0 |
| [2606:4700:99e6:84fc:bd92:ad89:3764:1531] | 80, 443, 8080 | 0 |
| [2606:4700:9a64:7143:8bdd:9979:d712:8709] | 80, 443, 8080 | 0 |
| [2606:4700:99e6:c629:7412:d7d4:81d2:5106] | 80, 443, 8080 | 1 |
| [2606:4700:8ddd:90eb:4b4c:7e4a:ca14:dfec] | 80, 443, 8080 | 1 |
| [2606:4700:99e6:c629:7412:d7d4:81d2:5106] | 80, 443, 8080 | 1 |
| [2606:4700:8ddd:90eb:4b4c:7e4a:ca14:dfec] | 80, 443, 8080 | 1 |
| [2606:4700:99e6:c629:7412:d7d4:81d2:5106] | 80, 443, 8080 | 1 |
| [2606:4700:8ddd:90eb:4b4c:7e4a:ca14:dfec] | 80, 443, 8080 | 1 |
| [2606:4700:83b1:d515:b2ba:51e4:db73:f3a5] | 80, 443, 8080 | 147 |
| [2606:4700:83b1:d515:b2ba:51e4:db73:f3a5] | 80, 443, 8080 | 147 |
| [2606:4700:83b1:d515:b2ba:51e4:db73:f3a5] | 80, 443, 8080 | 147 |

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
