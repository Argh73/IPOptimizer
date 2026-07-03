# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-04 01:09:24 +0330

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
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 198.41.223.142 | 80, 443, 8080 | 93 |
| 198.41.223.142 | 80, 443, 8080 | 93 |
| 198.41.223.142 | 80, 443, 8080 | 93 |
| 104.16.2.159 | 80, 443, 8080 | 130 |
| 104.18.240.89 | 80, 443, 8080 | 130 |
| 104.16.152.190 | 80, 443, 8080 | 130 |
| 104.16.2.159 | 80, 443, 8080 | 130 |
| 104.18.240.89 | 80, 443, 8080 | 130 |
| 104.16.152.190 | 80, 443, 8080 | 130 |
| 104.16.2.159 | 80, 443, 8080 | 130 |
| 104.18.240.89 | 80, 443, 8080 | 130 |
| 104.16.152.190 | 80, 443, 8080 | 130 |
| 104.19.204.126 | 80, 443, 8080 | 133 |
| 104.19.204.126 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9aed:103c:8169:111b:4486:496e] | 80, 443, 8080 | 1 |
| [2606:4700:91bb:832b:2eb0:2947:f50:a34c] | 80, 443, 8080 | 1 |
| [2606:4700:9aed:f03e:faba:8a2b:7f7d:ee66] | 80, 443, 8080 | 1 |
| [2606:4700:9aed:103c:8169:111b:4486:496e] | 80, 443, 8080 | 1 |
| [2606:4700:91bb:832b:2eb0:2947:f50:a34c] | 80, 443, 8080 | 1 |
| [2606:4700:9aed:f03e:faba:8a2b:7f7d:ee66] | 80, 443, 8080 | 1 |
| [2606:4700:9aed:103c:8169:111b:4486:496e] | 80, 443, 8080 | 1 |
| [2606:4700:91bb:832b:2eb0:2947:f50:a34c] | 80, 443, 8080 | 1 |
| [2606:4700:9aed:f03e:faba:8a2b:7f7d:ee66] | 80, 443, 8080 | 1 |
| [2606:4700:91bb:eecc:c56a:95c6:2b00:9155] | 80, 443, 8080 | 3 |
| [2606:4700:91bb:eecc:c56a:95c6:2b00:9155] | 80, 443, 8080 | 3 |
| [2606:4700:91bb:eecc:c56a:95c6:2b00:9155] | 80, 443, 8080 | 3 |
| [2606:4700:9:bf48:e2aa:f8c:b177:81c7] | 80, 443, 8080 | 4 |
| [2606:4700:9:bf48:e2aa:f8c:b177:81c7] | 80, 443, 8080 | 4 |
| [2606:4700:9:bf48:e2aa:f8c:b177:81c7] | 80, 443, 8080 | 4 |

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
