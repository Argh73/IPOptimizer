# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-27 20:24:15 +0330

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
| 104.19.85.243 | 80, 443, 8080 | 142 |
| 104.19.250.22 | 80, 443, 8080 | 143 |
| 104.19.121.152 | 80, 443, 8080 | 143 |
| 104.17.230.169 | 80, 443, 8080 | 150 |
| 104.19.79.33 | 80, 443, 8080 | 151 |
| 162.159.160.18 | 80, 443, 8080 | 157 |
| 162.159.160.18 | 80, 443, 8080 | 157 |
| 162.159.136.175 | 80, 443, 8080 | 162 |
| 162.159.136.175 | 80, 443, 8080 | 162 |
| 162.159.138.20 | 80, 443, 8080 | 163 |
| 162.159.128.146 | 80, 443, 8080 | 163 |
| 162.159.138.20 | 80, 443, 8080 | 163 |
| 162.159.128.146 | 80, 443, 8080 | 163 |
| 162.159.128.206 | 80, 443, 8080 | 166 |
| 162.159.128.206 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a69:5058:bf7a:f4a2:13eb:80e6] | 80, 443, 8080 | 4 |
| [2606:4700:9:ca37:fb89:5d88:e95:e50e] | 80, 443, 8080 | 4 |
| [2606:4700:3018:ad0d:bb37:6d49:250f:b87d] | 80, 443, 8080 | 4 |
| [2606:4700:90d0:a74:22a6:5856:9d85:6aa8] | 80, 443, 8080 | 4 |
| [2606:4700:99ea:c946:f354:c86a:99fe:7834] | 80, 443, 8080 | 4 |
| [2606:4700:9a69:5058:bf7a:f4a2:13eb:80e6] | 80, 443, 8080 | 4 |
| [2606:4700:9:ca37:fb89:5d88:e95:e50e] | 80, 443, 8080 | 4 |
| [2606:4700:3018:ad0d:bb37:6d49:250f:b87d] | 80, 443, 8080 | 4 |
| [2606:4700:90d0:a74:22a6:5856:9d85:6aa8] | 80, 443, 8080 | 4 |
| [2606:4700:99ea:c946:f354:c86a:99fe:7834] | 80, 443, 8080 | 4 |
| [2606:4700:9a69:5058:bf7a:f4a2:13eb:80e6] | 80, 443, 8080 | 4 |
| [2606:4700:9:ca37:fb89:5d88:e95:e50e] | 80, 443, 8080 | 4 |
| [2606:4700:3018:ad0d:bb37:6d49:250f:b87d] | 80, 443, 8080 | 4 |
| [2606:4700:90d0:a74:22a6:5856:9d85:6aa8] | 80, 443, 8080 | 4 |
| [2606:4700:99ea:c946:f354:c86a:99fe:7834] | 80, 443, 8080 | 4 |

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
