# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-15 17:42:59 +0330

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
| 104.16.86.95 | 80, 443, 8080 | 141 |
| 104.17.7.107 | 80, 443, 8080 | 142 |
| 162.159.253.28 | 80, 443, 8080 | 142 |
| 104.18.231.197 | 80, 443, 8080 | 142 |
| 104.17.91.26 | 80, 443, 8080 | 142 |
| 162.159.160.223 | 80, 443, 8080 | 150 |
| 162.159.160.223 | 80, 443, 8080 | 150 |
| 162.159.130.166 | 80, 443, 8080 | 166 |
| 162.159.136.212 | 80, 443, 8080 | 166 |
| 162.159.130.166 | 80, 443, 8080 | 166 |
| 162.159.136.212 | 80, 443, 8080 | 166 |
| 162.159.130.145 | 80, 443, 8080 | 167 |
| 162.159.130.145 | 80, 443, 8080 | 167 |
| 162.159.152.220 | 80, 443, 8080 | 169 |
| 162.159.152.220 | 80, 443, 8080 | 169 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9764:bc65:e777:a4d7:7bd5:ad59] | 80, 443, 8080 | 3 |
| [2606:4700:9764:8df:63f6:5faa:e454:f78e] | 80, 443, 8080 | 3 |
| [2606:4700:964e:e687:9fa5:f9e2:eaad:c146] | 80, 443, 8080 | 3 |
| [2606:4700:9764:bc65:e777:a4d7:7bd5:ad59] | 80, 443, 8080 | 3 |
| [2606:4700:9764:8df:63f6:5faa:e454:f78e] | 80, 443, 8080 | 3 |
| [2606:4700:964e:e687:9fa5:f9e2:eaad:c146] | 80, 443, 8080 | 3 |
| [2606:4700:9764:bc65:e777:a4d7:7bd5:ad59] | 80, 443, 8080 | 3 |
| [2606:4700:9764:8df:63f6:5faa:e454:f78e] | 80, 443, 8080 | 3 |
| [2606:4700:964e:e687:9fa5:f9e2:eaad:c146] | 80, 443, 8080 | 3 |
| [2606:4700:3027:58fc:7d10:337:6c55:2a5a] | 80, 443, 8080 | 12 |
| [2606:4700:3027:58fc:7d10:337:6c55:2a5a] | 80, 443, 8080 | 12 |
| [2606:4700:3027:58fc:7d10:337:6c55:2a5a] | 80, 443, 8080 | 12 |
| [2606:4700:3027:19fc:ff6c:f8e9:cd66:1ea4] | 80, 443, 8080 | 13 |
| [2606:4700:3027:19fc:ff6c:f8e9:cd66:1ea4] | 80, 443, 8080 | 13 |
| [2606:4700:3027:19fc:ff6c:f8e9:cd66:1ea4] | 80, 443, 8080 | 13 |

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
