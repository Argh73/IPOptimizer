# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-02 12:24:24 +0330

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
| 198.41.209.165 | 80, 443, 8080 | 50 |
| 198.41.209.50 | 80, 443, 8080 | 50 |
| 198.41.209.165 | 80, 443, 8080 | 50 |
| 198.41.209.50 | 80, 443, 8080 | 50 |
| 198.41.209.41 | 80, 443, 8080 | 52 |
| 198.41.209.41 | 80, 443, 8080 | 52 |
| 198.41.208.22 | 80, 443, 8080 | 53 |
| 198.41.208.22 | 80, 443, 8080 | 53 |
| 198.41.222.176 | 80, 443, 8080 | 67 |
| 198.41.208.49 | 80, 443, 8080 | 103 |
| 198.41.208.49 | 80, 443, 8080 | 103 |
| 104.18.8.44 | 80, 443, 8080 | 141 |
| 104.18.20.150 | 80, 443, 8080 | 142 |
| 104.18.74.90 | 80, 443, 8080 | 144 |
| 104.16.170.130 | 80, 443, 8080 | 151 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:22:e027:6f2a:42df:9e8:175a] | 80, 443, 8080 | 0 |
| [2606:4700:22:e027:6f2a:42df:9e8:175a] | 80, 443, 8080 | 0 |
| [2606:4700:22:e027:6f2a:42df:9e8:175a] | 80, 443, 8080 | 0 |
| [2606:4700:135:d8b8:6dda:67c4:3fe5:961b] | 80, 443, 8080 | 1 |
| [2606:4700:135:308d:cb4b:ad51:50b3:7d4a] | 80, 443, 8080 | 1 |
| [2606:4700:135:d8b8:6dda:67c4:3fe5:961b] | 80, 443, 8080 | 1 |
| [2606:4700:135:308d:cb4b:ad51:50b3:7d4a] | 80, 443, 8080 | 1 |
| [2606:4700:135:d8b8:6dda:67c4:3fe5:961b] | 80, 443, 8080 | 1 |
| [2606:4700:135:308d:cb4b:ad51:50b3:7d4a] | 80, 443, 8080 | 1 |
| [2606:4700:83bb:96be:d163:7336:7a6:ab88] | 80, 443, 8080 | 155 |
| [2606:4700:83bb:96be:d163:7336:7a6:ab88] | 80, 443, 8080 | 155 |
| [2606:4700:83bb:96be:d163:7336:7a6:ab88] | 80, 443, 8080 | 155 |
| [2606:4700:83bb:7533:3e29:5be2:34e6:9fe1] | 80, 443, 8080 | 156 |
| [2606:4700:83bb:7533:3e29:5be2:34e6:9fe1] | 80, 443, 8080 | 156 |
| [2606:4700:83bb:7533:3e29:5be2:34e6:9fe1] | 80, 443, 8080 | 156 |

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
