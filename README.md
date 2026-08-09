# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-09 11:02:29 +0330

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
| 198.41.209.240 | 80, 443, 8080 | 54 |
| 198.41.208.241 | 80, 443, 8080 | 54 |
| 198.41.209.240 | 80, 443, 8080 | 54 |
| 198.41.208.241 | 80, 443, 8080 | 54 |
| 198.41.208.5 | 80, 443, 8080 | 56 |
| 198.41.208.5 | 80, 443, 8080 | 56 |
| 198.41.222.67 | 80, 443, 8080 | 78 |
| 198.41.209.10 | 80, 443, 8080 | 124 |
| 198.41.209.10 | 80, 443, 8080 | 124 |
| 104.17.96.161 | 80, 443, 8080 | 141 |
| 172.64.86.56 | 80, 443, 8080 | 141 |
| 104.18.141.27 | 80, 443, 8080 | 142 |
| 104.17.166.48 | 80, 443, 8080 | 142 |
| 162.159.250.13 | 80, 443, 8080 | 182 |
| 162.159.250.13 | 80, 443, 8080 | 182 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8deb:27c0:292d:ae89:87a3:e208] | 80, 443, 8080 | 0 |
| [2606:4700:c:36cc:1e03:4852:ed97:b54d] | 80, 443, 8080 | 0 |
| [2606:4700:c:1b0c:c927:5ac6:b3d8:5151] | 80, 443, 8080 | 0 |
| [2606:4700:8deb:27c0:292d:ae89:87a3:e208] | 80, 443, 8080 | 0 |
| [2606:4700:c:36cc:1e03:4852:ed97:b54d] | 80, 443, 8080 | 0 |
| [2606:4700:c:1b0c:c927:5ac6:b3d8:5151] | 80, 443, 8080 | 0 |
| [2606:4700:8deb:27c0:292d:ae89:87a3:e208] | 80, 443, 8080 | 0 |
| [2606:4700:c:36cc:1e03:4852:ed97:b54d] | 80, 443, 8080 | 0 |
| [2606:4700:c:1b0c:c927:5ac6:b3d8:5151] | 80, 443, 8080 | 0 |
| [2606:4700:29:8339:b06b:dfee:f84a:dafb] | 80, 443, 8080 | 1 |
| [2606:4700:29:8339:b06b:dfee:f84a:dafb] | 80, 443, 8080 | 1 |
| [2606:4700:29:8339:b06b:dfee:f84a:dafb] | 80, 443, 8080 | 1 |
| [2606:4700:8ca9:529f:4152:55e7:1bba:2236] | 80, 443, 8080 | 134 |
| [2606:4700:8ca9:529f:4152:55e7:1bba:2236] | 80, 443, 8080 | 134 |
| [2606:4700:8ca9:529f:4152:55e7:1bba:2236] | 80, 443, 8080 | 134 |

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
