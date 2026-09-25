# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-25 15:34:38 +0330

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
| 198.41.222.208 | 80, 443, 8080 | 72 |
| 198.41.208.136 | 80, 443, 8080 | 75 |
| 198.41.208.136 | 80, 443, 8080 | 75 |
| 198.41.208.213 | 80, 443, 8080 | 116 |
| 198.41.208.213 | 80, 443, 8080 | 116 |
| 162.159.135.109 | 80, 443, 8080 | 138 |
| 162.159.135.109 | 80, 443, 8080 | 138 |
| 198.41.209.133 | 80, 443, 8080 | 140 |
| 198.41.209.133 | 80, 443, 8080 | 140 |
| 104.17.179.25 | 80, 443, 8080 | 142 |
| 104.16.126.57 | 80, 443, 8080 | 142 |
| 104.18.188.235 | 80, 443, 8080 | 143 |
| 104.16.1.182 | 80, 443, 8080 | 148 |
| 198.41.208.222 | 80, 443, 8080 | 150 |
| 198.41.208.222 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b05:40a3:c871:7a3c:8148:7558] | 80, 443, 8080 | 3 |
| [2606:4700:9ad1:6213:ff12:ef08:c781:5bbe] | 80, 443, 8080 | 3 |
| [2606:4700:91b5:71f2:e1ff:776b:f069:420e] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:9e6:5051:32ba:cc60:e111] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:9fa:e3ae:ab74:2b25:3188] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:40a3:c871:7a3c:8148:7558] | 80, 443, 8080 | 3 |
| [2606:4700:9ad1:6213:ff12:ef08:c781:5bbe] | 80, 443, 8080 | 3 |
| [2606:4700:91b5:71f2:e1ff:776b:f069:420e] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:9e6:5051:32ba:cc60:e111] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:9fa:e3ae:ab74:2b25:3188] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:40a3:c871:7a3c:8148:7558] | 80, 443, 8080 | 3 |
| [2606:4700:9ad1:6213:ff12:ef08:c781:5bbe] | 80, 443, 8080 | 3 |
| [2606:4700:91b5:71f2:e1ff:776b:f069:420e] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:9e6:5051:32ba:cc60:e111] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:9fa:e3ae:ab74:2b25:3188] | 80, 443, 8080 | 3 |

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
