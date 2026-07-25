# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-25 12:00:06 +0330

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
| 198.41.208.218 | 80, 443, 8080 | 49 |
| 198.41.208.218 | 80, 443, 8080 | 49 |
| 198.41.209.121 | 80, 443, 8080 | 50 |
| 198.41.209.121 | 80, 443, 8080 | 50 |
| 104.17.89.159 | 80, 443, 8080 | 164 |
| 104.25.186.222 | 80, 443, 8080 | 166 |
| 104.19.33.153 | 80, 443, 8080 | 168 |
| 104.19.37.18 | 80, 443, 8080 | 171 |
| 104.27.8.244 | 80, 443, 8080 | 175 |
| 172.64.86.28 | 80, 443, 8080 | 180 |
| 172.64.82.234 | 80, 443, 8080 | 180 |
| 172.64.86.28 | 80, 443, 8080 | 180 |
| 172.64.82.234 | 80, 443, 8080 | 180 |
| 172.67.180.201 | 80, 443, 8080 | 182 |
| 172.67.180.201 | 80, 443, 8080 | 182 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d95:3a7f:9f8b:ee6b:dec3:bd70] | 80, 443, 8080 | 0 |
| [2606:4700:9a97:3e21:b618:24d4:9031:9a0f] | 80, 443, 8080 | 0 |
| [2606:4700:8d95:3a7f:9f8b:ee6b:dec3:bd70] | 80, 443, 8080 | 0 |
| [2606:4700:9a97:3e21:b618:24d4:9031:9a0f] | 80, 443, 8080 | 0 |
| [2606:4700:8d95:3a7f:9f8b:ee6b:dec3:bd70] | 80, 443, 8080 | 0 |
| [2606:4700:9a97:3e21:b618:24d4:9031:9a0f] | 80, 443, 8080 | 0 |
| [2606:4700:9a97:175f:bd18:f13:efa1:8c28] | 80, 443, 8080 | 1 |
| [2606:4700:9a97:175f:bd18:f13:efa1:8c28] | 80, 443, 8080 | 1 |
| [2606:4700:9a97:175f:bd18:f13:efa1:8c28] | 80, 443, 8080 | 1 |
| [2606:4700:83b0:2a6c:53f4:eee4:b175:2ca1] | 80, 443, 8080 | 162 |
| [2606:4700:83b0:2a6c:53f4:eee4:b175:2ca1] | 80, 443, 8080 | 162 |
| [2606:4700:83b0:2a6c:53f4:eee4:b175:2ca1] | 80, 443, 8080 | 162 |
| [2606:4700:83b0:6d78:23be:4e78:5e0e:f2ca] | 80, 443, 8080 | 170 |
| [2606:4700:83b0:6d78:23be:4e78:5e0e:f2ca] | 80, 443, 8080 | 170 |
| [2606:4700:83b0:6d78:23be:4e78:5e0e:f2ca] | 80, 443, 8080 | 170 |

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
