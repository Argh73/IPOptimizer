# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-05 00:57:00 +0330

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
| 198.41.208.67 | 80, 443, 8080 | 58 |
| 198.41.222.59 | 80, 443, 8080 | 72 |
| 198.41.222.59 | 80, 443, 8080 | 72 |
| 198.41.222.59 | 80, 443, 8080 | 72 |
| 162.159.46.118 | 80, 443, 8080 | 75 |
| 162.159.46.118 | 80, 443, 8080 | 75 |
| 162.159.46.118 | 80, 443, 8080 | 75 |
| 104.16.217.39 | 80, 443, 8080 | 130 |
| 104.16.26.123 | 80, 443, 8080 | 130 |
| 104.16.217.39 | 80, 443, 8080 | 130 |
| 104.16.26.123 | 80, 443, 8080 | 130 |
| 104.16.217.39 | 80, 443, 8080 | 130 |
| 104.16.26.123 | 80, 443, 8080 | 130 |
| 104.16.224.212 | 80, 443, 8080 | 133 |
| 104.16.224.212 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dea:3e4:ac87:c6fb:9693:83e] | 80, 443, 8080 | 3 |
| [2606:4700:8dea:8e99:c604:e345:ba3:24a0] | 80, 443, 8080 | 3 |
| [2606:4700:13a:ea6a:8c10:ddd2:309a:da7e] | 80, 443, 8080 | 3 |
| [2606:4700:9648:3114:aea4:e52:5e77:f190] | 80, 443, 8080 | 3 |
| [2606:4700:9648:49a3:1150:4017:6b5a:f7f4] | 80, 443, 8080 | 3 |
| [2606:4700:8dea:3e4:ac87:c6fb:9693:83e] | 80, 443, 8080 | 3 |
| [2606:4700:8dea:8e99:c604:e345:ba3:24a0] | 80, 443, 8080 | 3 |
| [2606:4700:13a:ea6a:8c10:ddd2:309a:da7e] | 80, 443, 8080 | 3 |
| [2606:4700:9648:3114:aea4:e52:5e77:f190] | 80, 443, 8080 | 3 |
| [2606:4700:9648:49a3:1150:4017:6b5a:f7f4] | 80, 443, 8080 | 3 |
| [2606:4700:8dea:3e4:ac87:c6fb:9693:83e] | 80, 443, 8080 | 3 |
| [2606:4700:8dea:8e99:c604:e345:ba3:24a0] | 80, 443, 8080 | 3 |
| [2606:4700:13a:ea6a:8c10:ddd2:309a:da7e] | 80, 443, 8080 | 3 |
| [2606:4700:9648:3114:aea4:e52:5e77:f190] | 80, 443, 8080 | 3 |
| [2606:4700:9648:49a3:1150:4017:6b5a:f7f4] | 80, 443, 8080 | 3 |

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
