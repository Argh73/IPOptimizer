# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-15 03:33:59 +0330

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
| 198.41.211.67 | 80, 443, 8080 | 73 |
| 104.19.119.206 | 80, 443, 8080 | 138 |
| 104.18.203.214 | 80, 443, 8080 | 139 |
| 104.19.145.68 | 80, 443, 8080 | 139 |
| 104.16.234.144 | 80, 443, 8080 | 139 |
| 162.159.160.195 | 80, 443, 8080 | 148 |
| 162.159.160.195 | 80, 443, 8080 | 148 |
| 162.159.160.45 | 80, 443, 8080 | 150 |
| 162.159.160.45 | 80, 443, 8080 | 150 |
| 162.159.160.0 | 80, 443, 8080 | 154 |
| 162.159.160.0 | 80, 443, 8080 | 154 |
| 162.159.133.88 | 80, 443, 8080 | 167 |
| 162.159.133.88 | 80, 443, 8080 | 167 |
| 162.159.137.164 | 80, 443, 8080 | 168 |
| 162.159.137.164 | 80, 443, 8080 | 168 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3055:fecf:ee6c:eb0d:fc50:7988] | 80, 443, 8080 | 3 |
| [2606:4700:99e4:e4f6:556e:466d:7f6c:f03d] | 80, 443, 8080 | 3 |
| [2606:4700:3055:69e9:4ed7:8070:25ce:1ed9] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:f4:5323:e5d8:d829:591e] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:467c:2698:cf54:c68b:a8ba] | 80, 443, 8080 | 3 |
| [2606:4700:3055:fecf:ee6c:eb0d:fc50:7988] | 80, 443, 8080 | 3 |
| [2606:4700:99e4:e4f6:556e:466d:7f6c:f03d] | 80, 443, 8080 | 3 |
| [2606:4700:3055:69e9:4ed7:8070:25ce:1ed9] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:f4:5323:e5d8:d829:591e] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:467c:2698:cf54:c68b:a8ba] | 80, 443, 8080 | 3 |
| [2606:4700:3055:fecf:ee6c:eb0d:fc50:7988] | 80, 443, 8080 | 3 |
| [2606:4700:99e4:e4f6:556e:466d:7f6c:f03d] | 80, 443, 8080 | 3 |
| [2606:4700:3055:69e9:4ed7:8070:25ce:1ed9] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:f4:5323:e5d8:d829:591e] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:467c:2698:cf54:c68b:a8ba] | 80, 443, 8080 | 3 |

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
