# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-05 12:57:33 +0330

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
| 198.41.209.63 | 80, 443, 8080 | 55 |
| 198.41.209.63 | 80, 443, 8080 | 55 |
| 198.41.208.67 | 80, 443, 8080 | 58 |
| 198.41.208.67 | 80, 443, 8080 | 58 |
| 198.41.222.48 | 80, 443, 8080 | 75 |
| 198.41.223.19 | 80, 443, 8080 | 75 |
| 198.41.223.70 | 80, 443, 8080 | 77 |
| 198.41.222.226 | 80, 443, 8080 | 86 |
| 104.19.60.168 | 80, 443, 8080 | 131 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d98:8881:941e:959c:a1b4:859c] | 80, 443, 8080 | 3 |
| [2606:4700:90c8:8c5a:a817:4d61:d064:519] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:8e3:3c43:292c:4e55:6c76] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:8881:941e:959c:a1b4:859c] | 80, 443, 8080 | 3 |
| [2606:4700:90c8:8c5a:a817:4d61:d064:519] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:8e3:3c43:292c:4e55:6c76] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:8881:941e:959c:a1b4:859c] | 80, 443, 8080 | 3 |
| [2606:4700:90c8:8c5a:a817:4d61:d064:519] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:8e3:3c43:292c:4e55:6c76] | 80, 443, 8080 | 3 |
| [2606:4700:9c68:7ac6:f06e:906a:b6eb:5103] | 80, 443, 8080 | 4 |
| [2606:4700:9c68:7ac6:f06e:906a:b6eb:5103] | 80, 443, 8080 | 4 |
| [2606:4700:9c68:7ac6:f06e:906a:b6eb:5103] | 80, 443, 8080 | 4 |
| [2606:4700:4404:448d:86e7:83ec:6650:4d9b] | 80, 443, 8080 | 13 |
| [2606:4700:4404:448d:86e7:83ec:6650:4d9b] | 80, 443, 8080 | 13 |
| [2606:4700:4404:448d:86e7:83ec:6650:4d9b] | 80, 443, 8080 | 13 |

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
