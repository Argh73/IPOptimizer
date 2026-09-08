# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-09 02:22:29 +0330

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
| 198.41.208.62 | 80, 443, 8080 | 45 |
| 198.41.208.62 | 80, 443, 8080 | 45 |
| 198.41.209.10 | 80, 443, 8080 | 46 |
| 198.41.208.228 | 80, 443, 8080 | 46 |
| 198.41.209.10 | 80, 443, 8080 | 46 |
| 198.41.208.228 | 80, 443, 8080 | 46 |
| 198.41.208.48 | 80, 443, 8080 | 47 |
| 198.41.208.48 | 80, 443, 8080 | 47 |
| 198.41.209.100 | 80, 443, 8080 | 53 |
| 198.41.209.100 | 80, 443, 8080 | 53 |
| 162.159.36.36 | 80, 443, 8080 | 70 |
| 198.41.223.163 | 80, 443, 8080 | 76 |
| 104.21.236.63 | 80, 443, 8080 | 138 |
| 162.159.241.91 | 80, 443, 8080 | 140 |
| 104.17.50.2 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9769:ae53:9236:9874:9c00:db1b] | 80, 443, 8080 | 3 |
| [2606:4700:9a6e:5a11:154b:2be6:bcce:4f02] | 80, 443, 8080 | 3 |
| [2606:4700:964c:133d:33de:c4b1:d9fe:e03b] | 80, 443, 8080 | 3 |
| [2606:4700:964c:69d1:f87a:63a7:bbcb:1f6] | 80, 443, 8080 | 3 |
| [2606:4700:9769:ae53:9236:9874:9c00:db1b] | 80, 443, 8080 | 3 |
| [2606:4700:9a6e:5a11:154b:2be6:bcce:4f02] | 80, 443, 8080 | 3 |
| [2606:4700:964c:133d:33de:c4b1:d9fe:e03b] | 80, 443, 8080 | 3 |
| [2606:4700:964c:69d1:f87a:63a7:bbcb:1f6] | 80, 443, 8080 | 3 |
| [2606:4700:9769:ae53:9236:9874:9c00:db1b] | 80, 443, 8080 | 3 |
| [2606:4700:9a6e:5a11:154b:2be6:bcce:4f02] | 80, 443, 8080 | 3 |
| [2606:4700:964c:133d:33de:c4b1:d9fe:e03b] | 80, 443, 8080 | 3 |
| [2606:4700:964c:69d1:f87a:63a7:bbcb:1f6] | 80, 443, 8080 | 3 |
| [2606:4700:90c2:c371:e232:5c36:cea:af5d] | 80, 443, 8080 | 174 |
| [2606:4700:90c2:c371:e232:5c36:cea:af5d] | 80, 443, 8080 | 174 |
| [2606:4700:90c2:c371:e232:5c36:cea:af5d] | 80, 443, 8080 | 174 |

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
