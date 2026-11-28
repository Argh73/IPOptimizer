# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-28 06:22:21 +0330

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
| 104.19.87.187 | 80, 443, 8080 | 140 |
| 162.159.240.41 | 80, 443, 8080 | 142 |
| 172.64.89.118 | 80, 443, 8080 | 143 |
| 104.19.36.113 | 80, 443, 8080 | 144 |
| 198.41.215.198 | 80, 443, 8080 | 150 |
| 162.159.160.235 | 80, 443, 8080 | 154 |
| 162.159.160.235 | 80, 443, 8080 | 154 |
| 162.159.128.34 | 80, 443, 8080 | 161 |
| 162.159.128.113 | 80, 443, 8080 | 161 |
| 162.159.128.34 | 80, 443, 8080 | 161 |
| 162.159.128.113 | 80, 443, 8080 | 161 |
| 162.159.128.41 | 80, 443, 8080 | 162 |
| 162.159.128.90 | 80, 443, 8080 | 162 |
| 162.159.128.41 | 80, 443, 8080 | 162 |
| 162.159.128.90 | 80, 443, 8080 | 162 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c60:7224:c66d:961c:9c4d:a6de] | 80, 443, 8080 | 3 |
| [2606:4700:964a:eb4f:79d:ab5e:8d68:8ce1] | 80, 443, 8080 | 3 |
| [2606:4700:9c60:86a6:c7e2:16f1:5ea:db2] | 80, 443, 8080 | 3 |
| [2606:4700:964a:db35:5143:2f3:daef:93fd] | 80, 443, 8080 | 3 |
| [2606:4700:976a:d7a1:6016:efe5:f686:31cf] | 80, 443, 8080 | 3 |
| [2606:4700:9c60:7224:c66d:961c:9c4d:a6de] | 80, 443, 8080 | 3 |
| [2606:4700:964a:eb4f:79d:ab5e:8d68:8ce1] | 80, 443, 8080 | 3 |
| [2606:4700:9c60:86a6:c7e2:16f1:5ea:db2] | 80, 443, 8080 | 3 |
| [2606:4700:964a:db35:5143:2f3:daef:93fd] | 80, 443, 8080 | 3 |
| [2606:4700:976a:d7a1:6016:efe5:f686:31cf] | 80, 443, 8080 | 3 |
| [2606:4700:9c60:7224:c66d:961c:9c4d:a6de] | 80, 443, 8080 | 3 |
| [2606:4700:964a:eb4f:79d:ab5e:8d68:8ce1] | 80, 443, 8080 | 3 |
| [2606:4700:9c60:86a6:c7e2:16f1:5ea:db2] | 80, 443, 8080 | 3 |
| [2606:4700:964a:db35:5143:2f3:daef:93fd] | 80, 443, 8080 | 3 |
| [2606:4700:976a:d7a1:6016:efe5:f686:31cf] | 80, 443, 8080 | 3 |

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
