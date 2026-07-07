# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-07 13:36:15 +0330

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
| 198.41.209.213 | 80, 443, 8080 | 52 |
| 198.41.209.180 | 80, 443, 8080 | 52 |
| 198.41.209.213 | 80, 443, 8080 | 52 |
| 198.41.209.180 | 80, 443, 8080 | 52 |
| 198.41.209.228 | 80, 443, 8080 | 54 |
| 198.41.209.228 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 56 |
| 198.41.208.163 | 80, 443, 8080 | 56 |
| 198.41.209.145 | 80, 443, 8080 | 60 |
| 198.41.209.145 | 80, 443, 8080 | 60 |
| 198.41.223.135 | 80, 443, 8080 | 72 |
| 104.19.13.111 | 80, 443, 8080 | 131 |
| 104.19.232.99 | 80, 443, 8080 | 132 |
| 104.19.199.86 | 80, 443, 8080 | 132 |
| 104.19.31.204 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c64:a308:951b:ae3:dd5b:d6c4] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:b5c4:60b4:f8c8:9eef:545a] | 80, 443, 8080 | 3 |
| [2606:4700:9c64:70e6:c79f:c1ff:5662:f291] | 80, 443, 8080 | 3 |
| [2606:4700:9c64:a308:951b:ae3:dd5b:d6c4] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:b5c4:60b4:f8c8:9eef:545a] | 80, 443, 8080 | 3 |
| [2606:4700:9c64:70e6:c79f:c1ff:5662:f291] | 80, 443, 8080 | 3 |
| [2606:4700:9c64:a308:951b:ae3:dd5b:d6c4] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:b5c4:60b4:f8c8:9eef:545a] | 80, 443, 8080 | 3 |
| [2606:4700:9c64:70e6:c79f:c1ff:5662:f291] | 80, 443, 8080 | 3 |
| [2606:4700:9768:f7d7:7571:1227:9756:d358] | 80, 443, 8080 | 4 |
| [2606:4700:91bd:c94b:9ad3:4b61:b421:dece] | 80, 443, 8080 | 4 |
| [2606:4700:9768:f7d7:7571:1227:9756:d358] | 80, 443, 8080 | 4 |
| [2606:4700:91bd:c94b:9ad3:4b61:b421:dece] | 80, 443, 8080 | 4 |
| [2606:4700:9768:f7d7:7571:1227:9756:d358] | 80, 443, 8080 | 4 |
| [2606:4700:91bd:c94b:9ad3:4b61:b421:dece] | 80, 443, 8080 | 4 |

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
