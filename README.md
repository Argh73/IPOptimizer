# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-14 00:58:28 +0330

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
| 198.41.209.165 | 80, 443, 8080 | 49 |
| 198.41.209.165 | 80, 443, 8080 | 49 |
| 198.41.209.192 | 80, 443, 8080 | 52 |
| 198.41.209.192 | 80, 443, 8080 | 52 |
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.209.240 | 80, 443, 8080 | 55 |
| 198.41.209.240 | 80, 443, 8080 | 55 |
| 104.17.59.34 | 80, 443, 8080 | 138 |
| 104.19.109.50 | 80, 443, 8080 | 139 |
| 104.19.237.92 | 80, 443, 8080 | 140 |
| 104.17.90.58 | 80, 443, 8080 | 140 |
| 104.17.180.150 | 80, 443, 8080 | 142 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3039:b3cb:4d61:91d2:5b42:58cb] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:5980:ce78:916f:d718:a6e3] | 80, 443, 8080 | 3 |
| [2606:4700:3039:b3cb:4d61:91d2:5b42:58cb] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:5980:ce78:916f:d718:a6e3] | 80, 443, 8080 | 3 |
| [2606:4700:3039:b3cb:4d61:91d2:5b42:58cb] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:5980:ce78:916f:d718:a6e3] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:7466:c322:ff3e:1053:96ab] | 80, 443, 8080 | 4 |
| [2606:4700:8d9f:c89c:de3d:701a:8f63:d302] | 80, 443, 8080 | 4 |
| [2606:4700:9c6b:7466:c322:ff3e:1053:96ab] | 80, 443, 8080 | 4 |
| [2606:4700:8d9f:c89c:de3d:701a:8f63:d302] | 80, 443, 8080 | 4 |
| [2606:4700:9c6b:7466:c322:ff3e:1053:96ab] | 80, 443, 8080 | 4 |
| [2606:4700:8d9f:c89c:de3d:701a:8f63:d302] | 80, 443, 8080 | 4 |
| [2606:4700:3039:4dd6:b83d:43af:c9d6:5606] | 80, 443, 8080 | 13 |
| [2606:4700:3039:4dd6:b83d:43af:c9d6:5606] | 80, 443, 8080 | 13 |
| [2606:4700:3039:4dd6:b83d:43af:c9d6:5606] | 80, 443, 8080 | 13 |

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
