# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-25 13:21:45 +0330

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
| 198.41.209.94 | 80, 443, 8080 | 51 |
| 198.41.209.94 | 80, 443, 8080 | 51 |
| 198.41.208.112 | 80, 443, 8080 | 52 |
| 198.41.208.112 | 80, 443, 8080 | 52 |
| 198.41.209.41 | 80, 443, 8080 | 53 |
| 198.41.209.41 | 80, 443, 8080 | 53 |
| 198.41.208.201 | 80, 443, 8080 | 54 |
| 198.41.208.201 | 80, 443, 8080 | 54 |
| 162.159.46.158 | 80, 443, 8080 | 73 |
| 104.19.60.249 | 80, 443, 8080 | 132 |
| 104.19.48.147 | 80, 443, 8080 | 133 |
| 104.18.241.100 | 80, 443, 8080 | 133 |
| 104.18.104.87 | 80, 443, 8080 | 133 |
| 172.67.156.105 | 80, 443, 8080 | 199 |
| 172.67.156.105 | 80, 443, 8080 | 199 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d72:da09:f8f3:a97f:2676:a5da] | 80, 443, 8080 | 0 |
| [2606:4700:8ca6:51d7:3162:336a:35b8:4105] | 80, 443, 8080 | 0 |
| [2606:4700:8d90:fa29:57a0:1d3c:75c9:3601] | 80, 443, 8080 | 0 |
| [2606:4700:8d72:da09:f8f3:a97f:2676:a5da] | 80, 443, 8080 | 0 |
| [2606:4700:8ca6:51d7:3162:336a:35b8:4105] | 80, 443, 8080 | 0 |
| [2606:4700:8d90:fa29:57a0:1d3c:75c9:3601] | 80, 443, 8080 | 0 |
| [2606:4700:8d72:da09:f8f3:a97f:2676:a5da] | 80, 443, 8080 | 0 |
| [2606:4700:8ca6:51d7:3162:336a:35b8:4105] | 80, 443, 8080 | 0 |
| [2606:4700:8d90:fa29:57a0:1d3c:75c9:3601] | 80, 443, 8080 | 0 |
| [2606:4700:8d72:47d3:5c96:6eae:d4a6:e1d0] | 80, 443, 8080 | 1 |
| [2606:4700:13f:df9e:1b11:34d5:2e55:a73f] | 80, 443, 8080 | 1 |
| [2606:4700:8d72:47d3:5c96:6eae:d4a6:e1d0] | 80, 443, 8080 | 1 |
| [2606:4700:13f:df9e:1b11:34d5:2e55:a73f] | 80, 443, 8080 | 1 |
| [2606:4700:8d72:47d3:5c96:6eae:d4a6:e1d0] | 80, 443, 8080 | 1 |
| [2606:4700:13f:df9e:1b11:34d5:2e55:a73f] | 80, 443, 8080 | 1 |

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
