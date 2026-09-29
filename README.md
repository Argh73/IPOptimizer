# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-30 03:22:00 +0330

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
| 198.41.209.197 | 80, 443, 8080 | 51 |
| 198.41.209.170 | 80, 443, 8080 | 51 |
| 198.41.209.126 | 80, 443, 8080 | 54 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.208.16 | 80, 443, 8080 | 58 |
| 104.17.4.102 | 80, 443, 8080 | 139 |
| 104.17.230.198 | 80, 443, 8080 | 141 |
| 104.17.6.169 | 80, 443, 8080 | 141 |
| 104.16.172.183 | 80, 443, 8080 | 141 |
| 104.17.106.74 | 80, 443, 8080 | 143 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 172.67.116.91 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d77:506b:3890:14be:6bd3:d437] | 80, 443, 8080 | 12 |
| [2606:4700:9c66:8416:405:cfac:27b6:2a46] | 80, 443, 8080 | 12 |
| [2606:4700:9aea:5abe:f911:9540:ac4:10f2] | 80, 443, 8080 | 12 |
| [2606:4700:8d77:506b:3890:14be:6bd3:d437] | 80, 443, 8080 | 12 |
| [2606:4700:9c66:8416:405:cfac:27b6:2a46] | 80, 443, 8080 | 12 |
| [2606:4700:9aea:5abe:f911:9540:ac4:10f2] | 80, 443, 8080 | 12 |
| [2606:4700:8d77:506b:3890:14be:6bd3:d437] | 80, 443, 8080 | 12 |
| [2606:4700:9c66:8416:405:cfac:27b6:2a46] | 80, 443, 8080 | 12 |
| [2606:4700:9aea:5abe:f911:9540:ac4:10f2] | 80, 443, 8080 | 12 |
| [2606:4700:8ca2:9629:d6b0:5bc:7271:e174] | 80, 443, 8080 | 152 |
| [2606:4700:8ca2:9629:d6b0:5bc:7271:e174] | 80, 443, 8080 | 152 |
| [2606:4700:8ca2:9629:d6b0:5bc:7271:e174] | 80, 443, 8080 | 152 |
| [2606:4700:8ca2:a676:bef2:b2be:385a:fa6d] | 80, 443, 8080 | 153 |
| [2606:4700:8ca2:a676:bef2:b2be:385a:fa6d] | 80, 443, 8080 | 153 |
| [2606:4700:8ca2:a676:bef2:b2be:385a:fa6d] | 80, 443, 8080 | 153 |

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
