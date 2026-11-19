# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-19 05:26:37 +0330

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
| 104.19.103.116 | 80, 443, 8080 | 139 |
| 162.159.241.126 | 80, 443, 8080 | 141 |
| 104.19.46.30 | 80, 443, 8080 | 142 |
| 104.19.233.156 | 80, 443, 8080 | 151 |
| 162.159.160.191 | 80, 443, 8080 | 155 |
| 162.159.160.191 | 80, 443, 8080 | 155 |
| 104.25.72.174 | 80, 443, 8080 | 157 |
| 162.159.152.8 | 80, 443, 8080 | 167 |
| 162.159.152.8 | 80, 443, 8080 | 167 |
| 162.159.130.23 | 80, 443, 8080 | 169 |
| 162.159.136.30 | 80, 443, 8080 | 169 |
| 162.159.130.23 | 80, 443, 8080 | 169 |
| 162.159.136.30 | 80, 443, 8080 | 169 |
| 172.67.191.10 | 80, 443, 8080 | 183 |
| 172.67.191.10 | 80, 443, 8080 | 183 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:101:b0c:65d:9170:e523:853e] | 80, 443, 8080 | 3 |
| [2606:4700:3030:2c4:d1cb:e641:42b2:d56f] | 80, 443, 8080 | 3 |
| [2606:4700:91bc:46fa:b965:e079:917d:8108] | 80, 443, 8080 | 3 |
| [2606:4700:101:b0c:65d:9170:e523:853e] | 80, 443, 8080 | 3 |
| [2606:4700:3030:2c4:d1cb:e641:42b2:d56f] | 80, 443, 8080 | 3 |
| [2606:4700:91bc:46fa:b965:e079:917d:8108] | 80, 443, 8080 | 3 |
| [2606:4700:101:b0c:65d:9170:e523:853e] | 80, 443, 8080 | 3 |
| [2606:4700:3030:2c4:d1cb:e641:42b2:d56f] | 80, 443, 8080 | 3 |
| [2606:4700:91bc:46fa:b965:e079:917d:8108] | 80, 443, 8080 | 3 |
| [2606:4700:3030:a35f:1678:ad46:bb3d:ec57] | 80, 443, 8080 | 12 |
| [2606:4700:3030:a35f:1678:ad46:bb3d:ec57] | 80, 443, 8080 | 12 |
| [2606:4700:3030:a35f:1678:ad46:bb3d:ec57] | 80, 443, 8080 | 12 |
| [2606:4700:90c4:edc1:2a43:1ced:fd8f:183f] | 80, 443, 8080 | 157 |
| [2606:4700:90c4:edc1:2a43:1ced:fd8f:183f] | 80, 443, 8080 | 157 |
| [2606:4700:90c4:edc1:2a43:1ced:fd8f:183f] | 80, 443, 8080 | 157 |

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
