# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-19 10:50:31 +0330

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
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 104.17.110.22 | 80, 443, 8080 | 142 |
| 104.16.194.6 | 80, 443, 8080 | 142 |
| 104.18.158.217 | 80, 443, 8080 | 142 |
| 104.18.89.51 | 80, 443, 8080 | 142 |
| 104.16.102.33 | 80, 443, 8080 | 143 |
| 198.41.209.1 | 80, 443, 8080 | 167 |
| 198.41.209.1 | 80, 443, 8080 | 167 |
| 172.67.167.165 | 80, 443, 8080 | 190 |
| 172.67.167.165 | 80, 443, 8080 | 190 |
| 162.159.160.152 | 80, 443, 8080 | 192 |
| 162.159.160.152 | 80, 443, 8080 | 192 |
| 172.67.121.50 | 80, 443, 8080 | 201 |
| 172.67.121.50 | 80, 443, 8080 | 201 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d7f:3d77:e1f5:a0de:f0cc:698b] | 80, 443, 8080 | 0 |
| [2606:4700:8d7f:3d77:e1f5:a0de:f0cc:698b] | 80, 443, 8080 | 0 |
| [2606:4700:8d7f:3d77:e1f5:a0de:f0cc:698b] | 80, 443, 8080 | 0 |
| [2606:4700:130:b027:f6ff:4716:6832:d397] | 80, 443, 8080 | 1 |
| [2606:4700:8d7f:ea0d:6052:1479:17e5:3285] | 80, 443, 8080 | 1 |
| [2606:4700:130:9c30:7798:df22:3ef1:d3d2] | 80, 443, 8080 | 1 |
| [2606:4700:964f:6219:9868:9d1b:b906:18bc] | 80, 443, 8080 | 1 |
| [2606:4700:130:b027:f6ff:4716:6832:d397] | 80, 443, 8080 | 1 |
| [2606:4700:8d7f:ea0d:6052:1479:17e5:3285] | 80, 443, 8080 | 1 |
| [2606:4700:130:9c30:7798:df22:3ef1:d3d2] | 80, 443, 8080 | 1 |
| [2606:4700:964f:6219:9868:9d1b:b906:18bc] | 80, 443, 8080 | 1 |
| [2606:4700:130:b027:f6ff:4716:6832:d397] | 80, 443, 8080 | 1 |
| [2606:4700:8d7f:ea0d:6052:1479:17e5:3285] | 80, 443, 8080 | 1 |
| [2606:4700:130:9c30:7798:df22:3ef1:d3d2] | 80, 443, 8080 | 1 |
| [2606:4700:964f:6219:9868:9d1b:b906:18bc] | 80, 443, 8080 | 1 |

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
