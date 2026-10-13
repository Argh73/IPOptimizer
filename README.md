# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-13 17:58:22 +0330

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
| 198.41.222.237 | 80, 443, 8080 | 82 |
| 172.67.105.236 | 80, 443, 8080 | 136 |
| 172.67.105.236 | 80, 443, 8080 | 136 |
| 172.67.74.171 | 80, 443, 8080 | 137 |
| 172.67.74.171 | 80, 443, 8080 | 137 |
| 172.67.72.96 | 80, 443, 8080 | 138 |
| 172.67.72.96 | 80, 443, 8080 | 138 |
| 104.18.147.103 | 80, 443, 8080 | 143 |
| 172.64.67.245 | 80, 443, 8080 | 144 |
| 172.64.82.209 | 80, 443, 8080 | 144 |
| 104.17.8.232 | 80, 443, 8080 | 146 |
| 172.67.103.18 | 80, 443, 8080 | 162 |
| 172.67.103.18 | 80, 443, 8080 | 162 |
| 172.67.106.86 | 80, 443, 8080 | 164 |
| 172.67.106.86 | 80, 443, 8080 | 164 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d7d:fac8:27b9:af85:ceca:24ea] | 80, 443, 8080 | 3 |
| [2606:4700:8def:b31f:cb16:d618:930a:d98] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:1479:1942:8fc3:7d22:8069] | 80, 443, 8080 | 3 |
| [2606:4700:8def:497a:b54f:a278:3065:d84b] | 80, 443, 8080 | 3 |
| [2606:4700:9762:dbc6:15b4:5ea6:95cf:666] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:fac8:27b9:af85:ceca:24ea] | 80, 443, 8080 | 3 |
| [2606:4700:8def:b31f:cb16:d618:930a:d98] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:1479:1942:8fc3:7d22:8069] | 80, 443, 8080 | 3 |
| [2606:4700:8def:497a:b54f:a278:3065:d84b] | 80, 443, 8080 | 3 |
| [2606:4700:9762:dbc6:15b4:5ea6:95cf:666] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:fac8:27b9:af85:ceca:24ea] | 80, 443, 8080 | 3 |
| [2606:4700:8def:b31f:cb16:d618:930a:d98] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:1479:1942:8fc3:7d22:8069] | 80, 443, 8080 | 3 |
| [2606:4700:8def:497a:b54f:a278:3065:d84b] | 80, 443, 8080 | 3 |
| [2606:4700:9762:dbc6:15b4:5ea6:95cf:666] | 80, 443, 8080 | 3 |

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
