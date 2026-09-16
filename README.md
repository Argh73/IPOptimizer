# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-16 15:26:07 +0330

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
| 198.41.208.127 | 80, 443, 8080 | 47 |
| 198.41.208.127 | 80, 443, 8080 | 47 |
| 198.41.208.63 | 80, 443, 8080 | 49 |
| 198.41.208.63 | 80, 443, 8080 | 49 |
| 198.41.209.231 | 80, 443, 8080 | 56 |
| 198.41.209.231 | 80, 443, 8080 | 56 |
| 198.41.209.225 | 80, 443, 8080 | 74 |
| 198.41.209.225 | 80, 443, 8080 | 74 |
| 198.41.209.2 | 80, 443, 8080 | 75 |
| 198.41.209.2 | 80, 443, 8080 | 75 |
| 198.41.222.42 | 80, 443, 8080 | 78 |
| 198.41.223.253 | 80, 443, 8080 | 83 |
| 198.41.211.219 | 80, 443, 8080 | 90 |
| 198.41.222.141 | 80, 443, 8080 | 98 |
| 104.18.255.91 | 80, 443, 8080 | 141 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91b7:17ad:a9ae:d46b:b625:85f9] | 80, 443, 8080 | 3 |
| [2606:4700:90df:c019:3c84:4e73:10c8:82ee] | 80, 443, 8080 | 3 |
| [2606:4700:91b3:526d:3ed2:c643:405e:45a6] | 80, 443, 8080 | 3 |
| [2606:4700:3010:45b8:3621:ac21:8d95:dbfc] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:17ad:a9ae:d46b:b625:85f9] | 80, 443, 8080 | 3 |
| [2606:4700:90df:c019:3c84:4e73:10c8:82ee] | 80, 443, 8080 | 3 |
| [2606:4700:91b3:526d:3ed2:c643:405e:45a6] | 80, 443, 8080 | 3 |
| [2606:4700:3010:45b8:3621:ac21:8d95:dbfc] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:17ad:a9ae:d46b:b625:85f9] | 80, 443, 8080 | 3 |
| [2606:4700:90df:c019:3c84:4e73:10c8:82ee] | 80, 443, 8080 | 3 |
| [2606:4700:91b3:526d:3ed2:c643:405e:45a6] | 80, 443, 8080 | 3 |
| [2606:4700:3010:45b8:3621:ac21:8d95:dbfc] | 80, 443, 8080 | 3 |
| [2606:4700:3010:c0dd:c067:9ea7:5dab:9d6] | 80, 443, 8080 | 13 |
| [2606:4700:3010:c0dd:c067:9ea7:5dab:9d6] | 80, 443, 8080 | 13 |
| [2606:4700:3010:c0dd:c067:9ea7:5dab:9d6] | 80, 443, 8080 | 13 |

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
