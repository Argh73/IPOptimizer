# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-14 03:17:45 +0330

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
| 198.41.208.32 | 80, 443, 8080 | 51 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.208.109 | 80, 443, 8080 | 59 |
| 172.67.98.176 | 80, 443, 8080 | 93 |
| 172.67.107.253 | 80, 443, 8080 | 94 |
| 172.67.101.166 | 80, 443, 8080 | 95 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.19.37.79 | 80, 443, 8080 | 146 |
| 104.19.103.94 | 80, 443, 8080 | 148 |
| 104.25.137.232 | 80, 443, 8080 | 153 |
| 104.27.5.91 | 80, 443, 8080 | 153 |
| 104.19.204.153 | 80, 443, 8080 | 155 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dd3:9079:52a0:a513:ad1a:45b] | 80, 443, 8080 | 3 |
| [2606:4700:9ad8:6f2f:a808:236:651:b538] | 80, 443, 8080 | 3 |
| [2606:4700:8dd3:72d0:5314:2460:43af:c85e] | 80, 443, 8080 | 3 |
| [2606:4700:300b:7f05:4a40:6196:667:ee62] | 80, 443, 8080 | 3 |
| [2606:4700:9b04:e9c2:933a:49f5:2ef0:2cd4] | 80, 443, 8080 | 3 |
| [2606:4700:8dd3:9079:52a0:a513:ad1a:45b] | 80, 443, 8080 | 3 |
| [2606:4700:9ad8:6f2f:a808:236:651:b538] | 80, 443, 8080 | 3 |
| [2606:4700:8dd3:72d0:5314:2460:43af:c85e] | 80, 443, 8080 | 3 |
| [2606:4700:300b:7f05:4a40:6196:667:ee62] | 80, 443, 8080 | 3 |
| [2606:4700:9b04:e9c2:933a:49f5:2ef0:2cd4] | 80, 443, 8080 | 3 |
| [2606:4700:8dd3:9079:52a0:a513:ad1a:45b] | 80, 443, 8080 | 3 |
| [2606:4700:9ad8:6f2f:a808:236:651:b538] | 80, 443, 8080 | 3 |
| [2606:4700:8dd3:72d0:5314:2460:43af:c85e] | 80, 443, 8080 | 3 |
| [2606:4700:300b:7f05:4a40:6196:667:ee62] | 80, 443, 8080 | 3 |
| [2606:4700:9b04:e9c2:933a:49f5:2ef0:2cd4] | 80, 443, 8080 | 3 |

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
