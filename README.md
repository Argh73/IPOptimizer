# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-27 06:32:50 +0330

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
| 104.19.37.216 | 80, 443, 8080 | 140 |
| 104.19.6.220 | 80, 443, 8080 | 141 |
| 104.19.221.173 | 80, 443, 8080 | 141 |
| 104.19.95.55 | 80, 443, 8080 | 142 |
| 162.159.160.102 | 80, 443, 8080 | 148 |
| 162.159.160.102 | 80, 443, 8080 | 148 |
| 162.159.160.130 | 80, 443, 8080 | 153 |
| 162.159.160.130 | 80, 443, 8080 | 153 |
| 162.159.160.145 | 80, 443, 8080 | 155 |
| 162.159.160.145 | 80, 443, 8080 | 155 |
| 162.159.160.237 | 80, 443, 8080 | 156 |
| 162.159.160.237 | 80, 443, 8080 | 156 |
| 162.159.130.216 | 80, 443, 8080 | 161 |
| 104.24.147.85 | 80, 443, 8080 | 161 |
| 162.159.130.216 | 80, 443, 8080 | 161 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a9b:8897:a71a:2122:fbc9:fde6] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:11df:1aa:5eed:bd31:d5c0] | 80, 443, 8080 | 3 |
| [2606:4700:9a6b:417b:76ca:188f:7615:f878] | 80, 443, 8080 | 3 |
| [2606:4700:9a6b:818c:807b:b823:1fdd:75cc] | 80, 443, 8080 | 3 |
| [2606:4700:9a9b:8897:a71a:2122:fbc9:fde6] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:11df:1aa:5eed:bd31:d5c0] | 80, 443, 8080 | 3 |
| [2606:4700:9a6b:417b:76ca:188f:7615:f878] | 80, 443, 8080 | 3 |
| [2606:4700:9a6b:818c:807b:b823:1fdd:75cc] | 80, 443, 8080 | 3 |
| [2606:4700:9a9b:8897:a71a:2122:fbc9:fde6] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:11df:1aa:5eed:bd31:d5c0] | 80, 443, 8080 | 3 |
| [2606:4700:9a6b:417b:76ca:188f:7615:f878] | 80, 443, 8080 | 3 |
| [2606:4700:9a6b:818c:807b:b823:1fdd:75cc] | 80, 443, 8080 | 3 |
| [2606:4700:3034:8ee8:97ba:7016:8789:bd9d] | 80, 443, 8080 | 13 |
| [2606:4700:3034:8ee8:97ba:7016:8789:bd9d] | 80, 443, 8080 | 13 |
| [2606:4700:3034:8ee8:97ba:7016:8789:bd9d] | 80, 443, 8080 | 13 |

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
