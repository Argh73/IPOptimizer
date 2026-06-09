# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-09 13:39:09 +0330

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
| 198.41.208.236 | 80, 443, 8080 | 55 |
| 198.41.211.151 | 80, 443, 8080 | 88 |
| 198.41.211.151 | 80, 443, 8080 | 88 |
| 198.41.211.151 | 80, 443, 8080 | 88 |
| 104.18.12.104 | 80, 443, 8080 | 132 |
| 104.18.12.104 | 80, 443, 8080 | 132 |
| 104.18.12.104 | 80, 443, 8080 | 132 |
| 104.17.56.87 | 80, 443, 8080 | 133 |
| 104.17.78.72 | 80, 443, 8080 | 133 |
| 104.17.208.214 | 80, 443, 8080 | 133 |
| 104.17.56.87 | 80, 443, 8080 | 133 |
| 104.17.78.72 | 80, 443, 8080 | 133 |
| 104.17.208.214 | 80, 443, 8080 | 133 |
| 104.17.56.87 | 80, 443, 8080 | 133 |
| 104.17.78.72 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90d3:29ae:b9be:b5ed:e4b4:17e8] | 80, 443, 8080 | 3 |
| [2606:4700:90d3:2e8a:24f5:7646:b060:f4e] | 80, 443, 8080 | 3 |
| [2606:4700:90c7:6443:5a63:82f3:d3c9:13e] | 80, 443, 8080 | 3 |
| [2606:4700:90c7:8f96:874f:21b5:c006:5762] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:db2d:d7f0:b369:5a5b:1a6] | 80, 443, 8080 | 3 |
| [2606:4700:90d3:29ae:b9be:b5ed:e4b4:17e8] | 80, 443, 8080 | 3 |
| [2606:4700:90d3:2e8a:24f5:7646:b060:f4e] | 80, 443, 8080 | 3 |
| [2606:4700:90c7:6443:5a63:82f3:d3c9:13e] | 80, 443, 8080 | 3 |
| [2606:4700:90c7:8f96:874f:21b5:c006:5762] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:db2d:d7f0:b369:5a5b:1a6] | 80, 443, 8080 | 3 |
| [2606:4700:90d3:29ae:b9be:b5ed:e4b4:17e8] | 80, 443, 8080 | 3 |
| [2606:4700:90d3:2e8a:24f5:7646:b060:f4e] | 80, 443, 8080 | 3 |
| [2606:4700:90c7:6443:5a63:82f3:d3c9:13e] | 80, 443, 8080 | 3 |
| [2606:4700:90c7:8f96:874f:21b5:c006:5762] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:db2d:d7f0:b369:5a5b:1a6] | 80, 443, 8080 | 3 |

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
