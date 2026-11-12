# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-12 18:59:58 +0330

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
| 198.41.208.41 | 80, 443, 8080 | 116 |
| 198.41.208.41 | 80, 443, 8080 | 116 |
| 198.41.209.128 | 80, 443, 8080 | 142 |
| 104.16.12.249 | 80, 443, 8080 | 142 |
| 104.19.96.229 | 80, 443, 8080 | 142 |
| 198.41.209.128 | 80, 443, 8080 | 142 |
| 104.17.90.114 | 80, 443, 8080 | 143 |
| 104.17.107.6 | 80, 443, 8080 | 143 |
| 162.159.160.73 | 80, 443, 8080 | 148 |
| 162.159.160.35 | 80, 443, 8080 | 148 |
| 162.159.160.73 | 80, 443, 8080 | 148 |
| 162.159.160.35 | 80, 443, 8080 | 148 |
| 198.41.208.35 | 80, 443, 8080 | 150 |
| 198.41.208.35 | 80, 443, 8080 | 150 |
| 104.16.10.10 | 80, 443, 8080 | 152 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ae6:5e59:d22a:7ceb:b4c7:665a] | 80, 443, 8080 | 3 |
| [2606:4700:90da:3dca:ffc1:2e52:acd0:5028] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:5e59:d22a:7ceb:b4c7:665a] | 80, 443, 8080 | 3 |
| [2606:4700:90da:3dca:ffc1:2e52:acd0:5028] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:5e59:d22a:7ceb:b4c7:665a] | 80, 443, 8080 | 3 |
| [2606:4700:90da:3dca:ffc1:2e52:acd0:5028] | 80, 443, 8080 | 3 |
| [2606:4700:8ca1:d65b:d3df:62d5:8331:deb6] | 80, 443, 8080 | 136 |
| [2606:4700:8ca1:d65b:d3df:62d5:8331:deb6] | 80, 443, 8080 | 136 |
| [2606:4700:8ca1:d65b:d3df:62d5:8331:deb6] | 80, 443, 8080 | 136 |
| [2606:4700:83b8:342d:cc20:23ea:a16f:f9e3] | 80, 443, 8080 | 145 |
| [2606:4700:83b8:342d:cc20:23ea:a16f:f9e3] | 80, 443, 8080 | 145 |
| [2606:4700:83b8:342d:cc20:23ea:a16f:f9e3] | 80, 443, 8080 | 145 |
| [2606:4700:83b8:a2e8:a614:fd16:1df6:560] | 80, 443, 8080 | 164 |
| [2606:4700:83b8:a2e8:a614:fd16:1df6:560] | 80, 443, 8080 | 164 |
| [2606:4700:83b8:a2e8:a614:fd16:1df6:560] | 80, 443, 8080 | 164 |

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
