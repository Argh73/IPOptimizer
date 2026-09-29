# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-29 16:43:00 +0330

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
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.209.34 | 80, 443, 8080 | 71 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.17.173.69 | 80, 443, 8080 | 151 |
| 104.18.175.31 | 80, 443, 8080 | 152 |
| 104.18.124.137 | 80, 443, 8080 | 152 |
| 104.19.241.224 | 80, 443, 8080 | 153 |
| 104.16.193.21 | 80, 443, 8080 | 153 |
| 162.159.128.34 | 80, 443, 8080 | 162 |
| 162.159.130.128 | 80, 443, 8080 | 163 |
| 162.159.135.231 | 80, 443, 8080 | 163 |
| 162.159.134.151 | 80, 443, 8080 | 165 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3021:4398:a426:ee53:6607:bbbd] | 80, 443, 8080 | 3 |
| [2606:4700:99e9:b46d:ac4:b826:abef:8652] | 80, 443, 8080 | 3 |
| [2606:4700:99e9:c8bc:d465:87fa:73bc:9a7d] | 80, 443, 8080 | 3 |
| [2606:4700:8dda:a983:6ba8:9c0e:448a:702a] | 80, 443, 8080 | 3 |
| [2606:4700:8dda:2954:5165:f047:d5b:beb0] | 80, 443, 8080 | 3 |
| [2606:4700:3021:4398:a426:ee53:6607:bbbd] | 80, 443, 8080 | 3 |
| [2606:4700:99e9:b46d:ac4:b826:abef:8652] | 80, 443, 8080 | 3 |
| [2606:4700:99e9:c8bc:d465:87fa:73bc:9a7d] | 80, 443, 8080 | 3 |
| [2606:4700:8dda:a983:6ba8:9c0e:448a:702a] | 80, 443, 8080 | 3 |
| [2606:4700:8dda:2954:5165:f047:d5b:beb0] | 80, 443, 8080 | 3 |
| [2606:4700:3021:4398:a426:ee53:6607:bbbd] | 80, 443, 8080 | 3 |
| [2606:4700:99e9:b46d:ac4:b826:abef:8652] | 80, 443, 8080 | 3 |
| [2606:4700:99e9:c8bc:d465:87fa:73bc:9a7d] | 80, 443, 8080 | 3 |
| [2606:4700:8dda:a983:6ba8:9c0e:448a:702a] | 80, 443, 8080 | 3 |
| [2606:4700:8dda:2954:5165:f047:d5b:beb0] | 80, 443, 8080 | 3 |

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
