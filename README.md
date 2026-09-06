# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-06 14:44:36 +0330

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
| 198.41.209.36 | 80, 443, 8080 | 48 |
| 198.41.209.172 | 80, 443, 8080 | 48 |
| 198.41.209.36 | 80, 443, 8080 | 48 |
| 198.41.209.172 | 80, 443, 8080 | 48 |
| 198.41.209.168 | 80, 443, 8080 | 68 |
| 198.41.209.241 | 80, 443, 8080 | 68 |
| 198.41.209.168 | 80, 443, 8080 | 68 |
| 198.41.209.241 | 80, 443, 8080 | 68 |
| 198.41.209.50 | 80, 443, 8080 | 77 |
| 198.41.209.50 | 80, 443, 8080 | 77 |
| 198.41.222.73 | 80, 443, 8080 | 78 |
| 162.159.36.66 | 80, 443, 8080 | 80 |
| 172.64.85.14 | 80, 443, 8080 | 141 |
| 104.18.82.80 | 80, 443, 8080 | 143 |
| 104.16.65.195 | 80, 443, 8080 | 149 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a63:49ac:baf4:5a20:1908:74a5] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:b03d:ecae:fecc:6295:a707] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:e16b:607c:eda7:882b:2548] | 80, 443, 8080 | 3 |
| [2606:4700:9a63:7875:f6a8:acb3:a093:4e1c] | 80, 443, 8080 | 3 |
| [2606:4700:976d:1546:2dbb:97d4:4a13:ecc1] | 80, 443, 8080 | 3 |
| [2606:4700:9a63:49ac:baf4:5a20:1908:74a5] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:b03d:ecae:fecc:6295:a707] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:e16b:607c:eda7:882b:2548] | 80, 443, 8080 | 3 |
| [2606:4700:9a63:7875:f6a8:acb3:a093:4e1c] | 80, 443, 8080 | 3 |
| [2606:4700:976d:1546:2dbb:97d4:4a13:ecc1] | 80, 443, 8080 | 3 |
| [2606:4700:9a63:49ac:baf4:5a20:1908:74a5] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:b03d:ecae:fecc:6295:a707] | 80, 443, 8080 | 3 |
| [2606:4700:9a94:e16b:607c:eda7:882b:2548] | 80, 443, 8080 | 3 |
| [2606:4700:9a63:7875:f6a8:acb3:a093:4e1c] | 80, 443, 8080 | 3 |
| [2606:4700:976d:1546:2dbb:97d4:4a13:ecc1] | 80, 443, 8080 | 3 |

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
