# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-18 01:49:52 +0330

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
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.208.181 | 80, 443, 8080 | 54 |
| 198.41.208.45 | 80, 443, 8080 | 54 |
| 198.41.208.181 | 80, 443, 8080 | 54 |
| 198.41.208.45 | 80, 443, 8080 | 54 |
| 162.159.46.60 | 80, 443, 8080 | 79 |
| 104.17.249.68 | 80, 443, 8080 | 129 |
| 104.17.90.175 | 80, 443, 8080 | 130 |
| 104.17.199.187 | 80, 443, 8080 | 130 |
| 104.16.98.177 | 80, 443, 8080 | 130 |
| 172.67.160.101 | 80, 443, 8080 | 191 |
| 172.67.160.101 | 80, 443, 8080 | 191 |
| 172.67.70.77 | 80, 443, 8080 | 194 |
| 172.67.70.77 | 80, 443, 8080 | 194 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:131:ef34:dcf:b25a:b532:b58f] | 80, 443, 8080 | 0 |
| [2606:4700:3056:a9f1:d357:efb8:1733:159c] | 80, 443, 8080 | 0 |
| [2606:4700:3056:8b54:7a9d:6a2a:e5dd:fd3f] | 80, 443, 8080 | 0 |
| [2606:4700:131:ef34:dcf:b25a:b532:b58f] | 80, 443, 8080 | 0 |
| [2606:4700:3056:a9f1:d357:efb8:1733:159c] | 80, 443, 8080 | 0 |
| [2606:4700:3056:8b54:7a9d:6a2a:e5dd:fd3f] | 80, 443, 8080 | 0 |
| [2606:4700:131:ef34:dcf:b25a:b532:b58f] | 80, 443, 8080 | 0 |
| [2606:4700:3056:a9f1:d357:efb8:1733:159c] | 80, 443, 8080 | 0 |
| [2606:4700:3056:8b54:7a9d:6a2a:e5dd:fd3f] | 80, 443, 8080 | 0 |
| [2606:4700:8d99:a1e8:1148:368f:6e09:b83e] | 80, 443, 8080 | 1 |
| [2606:4700:8d99:657f:80a2:5a7d:d6cc:858d] | 80, 443, 8080 | 1 |
| [2606:4700:8d99:a1e8:1148:368f:6e09:b83e] | 80, 443, 8080 | 1 |
| [2606:4700:8d99:657f:80a2:5a7d:d6cc:858d] | 80, 443, 8080 | 1 |
| [2606:4700:8d99:a1e8:1148:368f:6e09:b83e] | 80, 443, 8080 | 1 |
| [2606:4700:8d99:657f:80a2:5a7d:d6cc:858d] | 80, 443, 8080 | 1 |

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
