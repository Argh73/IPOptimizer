# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-25 01:23:17 +0330

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
| 198.41.209.170 | 80, 443, 8080 | 52 |
| 198.41.208.112 | 80, 443, 8080 | 52 |
| 198.41.209.170 | 80, 443, 8080 | 52 |
| 198.41.208.112 | 80, 443, 8080 | 52 |
| 198.41.209.41 | 80, 443, 8080 | 53 |
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.209.41 | 80, 443, 8080 | 53 |
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.208.201 | 80, 443, 8080 | 54 |
| 198.41.208.201 | 80, 443, 8080 | 54 |
| 198.41.222.68 | 80, 443, 8080 | 83 |
| 104.19.47.167 | 80, 443, 8080 | 130 |
| 104.18.177.206 | 80, 443, 8080 | 130 |
| 190.93.244.78 | 80, 443, 8080 | 130 |
| 104.16.91.177 | 80, 443, 8080 | 131 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3031:e7fe:5884:aaa1:8923:db6] | 80, 443, 8080 | 0 |
| [2606:4700:16:70be:cdfb:a0b8:4d28:37ab] | 80, 443, 8080 | 0 |
| [2606:4700:9a94:7dea:d2e3:d6b5:47b1:8c24] | 80, 443, 8080 | 0 |
| [2606:4700:3031:e7fe:5884:aaa1:8923:db6] | 80, 443, 8080 | 0 |
| [2606:4700:16:70be:cdfb:a0b8:4d28:37ab] | 80, 443, 8080 | 0 |
| [2606:4700:9a94:7dea:d2e3:d6b5:47b1:8c24] | 80, 443, 8080 | 0 |
| [2606:4700:3031:e7fe:5884:aaa1:8923:db6] | 80, 443, 8080 | 0 |
| [2606:4700:16:70be:cdfb:a0b8:4d28:37ab] | 80, 443, 8080 | 0 |
| [2606:4700:9a94:7dea:d2e3:d6b5:47b1:8c24] | 80, 443, 8080 | 0 |
| [2606:4700:9ad5:ebb9:53e1:e173:d03b:9da0] | 80, 443, 8080 | 1 |
| [2606:4700:9aef:8d32:b9d0:bb08:9754:5b71] | 80, 443, 8080 | 1 |
| [2606:4700:9ad5:ebb9:53e1:e173:d03b:9da0] | 80, 443, 8080 | 1 |
| [2606:4700:9aef:8d32:b9d0:bb08:9754:5b71] | 80, 443, 8080 | 1 |
| [2606:4700:9ad5:ebb9:53e1:e173:d03b:9da0] | 80, 443, 8080 | 1 |
| [2606:4700:9aef:8d32:b9d0:bb08:9754:5b71] | 80, 443, 8080 | 1 |

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
