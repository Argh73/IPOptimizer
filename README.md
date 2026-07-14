# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-14 12:06:07 +0330

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
| 198.41.209.149 | 80, 443, 8080 | 51 |
| 198.41.209.149 | 80, 443, 8080 | 51 |
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.209.242 | 80, 443, 8080 | 58 |
| 198.41.209.242 | 80, 443, 8080 | 58 |
| 104.17.185.162 | 80, 443, 8080 | 143 |
| 104.16.80.134 | 80, 443, 8080 | 151 |
| 104.16.21.253 | 80, 443, 8080 | 152 |
| 104.16.84.94 | 80, 443, 8080 | 154 |
| 104.27.40.208 | 80, 443, 8080 | 157 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c6f:c6e8:c5ae:843f:50c:a0cb] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:fa5c:4d94:fc64:f3c0:f97d] | 80, 443, 8080 | 0 |
| [2606:4700:d:a893:3772:54c1:e0d8:e0e5] | 80, 443, 8080 | 0 |
| [2606:4700:9641:dce0:37a2:e55:ab79:c7cb] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:c6e8:c5ae:843f:50c:a0cb] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:fa5c:4d94:fc64:f3c0:f97d] | 80, 443, 8080 | 0 |
| [2606:4700:d:a893:3772:54c1:e0d8:e0e5] | 80, 443, 8080 | 0 |
| [2606:4700:9641:dce0:37a2:e55:ab79:c7cb] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:c6e8:c5ae:843f:50c:a0cb] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:fa5c:4d94:fc64:f3c0:f97d] | 80, 443, 8080 | 0 |
| [2606:4700:d:a893:3772:54c1:e0d8:e0e5] | 80, 443, 8080 | 0 |
| [2606:4700:9641:dce0:37a2:e55:ab79:c7cb] | 80, 443, 8080 | 0 |
| [2606:4700:d:7de7:9a2a:e3a:63e:bb4] | 80, 443, 8080 | 1 |
| [2606:4700:d:7de7:9a2a:e3a:63e:bb4] | 80, 443, 8080 | 1 |
| [2606:4700:d:7de7:9a2a:e3a:63e:bb4] | 80, 443, 8080 | 1 |

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
