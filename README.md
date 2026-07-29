# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-30 00:55:44 +0330

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
| 198.41.208.41 | 80, 443, 8080 | 52 |
| 198.41.208.41 | 80, 443, 8080 | 52 |
| 198.41.208.150 | 80, 443, 8080 | 54 |
| 198.41.208.2 | 80, 443, 8080 | 54 |
| 198.41.208.87 | 80, 443, 8080 | 54 |
| 198.41.208.150 | 80, 443, 8080 | 54 |
| 198.41.208.2 | 80, 443, 8080 | 54 |
| 198.41.208.87 | 80, 443, 8080 | 54 |
| 198.41.208.125 | 80, 443, 8080 | 56 |
| 198.41.208.125 | 80, 443, 8080 | 56 |
| 104.17.62.17 | 80, 443, 8080 | 138 |
| 104.16.218.64 | 80, 443, 8080 | 138 |
| 104.16.217.114 | 80, 443, 8080 | 139 |
| 104.18.27.54 | 80, 443, 8080 | 140 |
| 104.17.120.104 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d95:f1f5:272c:bcea:eccd:6e7e] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:2bdb:1d36:416b:8de3:3d8e] | 80, 443, 8080 | 3 |
| [2606:4700:9768:b85:6d2d:f0fa:a5cb:cec7] | 80, 443, 8080 | 3 |
| [2606:4700:3015:fa1:b5b8:31e2:1f22:833f] | 80, 443, 8080 | 3 |
| [2606:4700:8d95:f1f5:272c:bcea:eccd:6e7e] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:2bdb:1d36:416b:8de3:3d8e] | 80, 443, 8080 | 3 |
| [2606:4700:9768:b85:6d2d:f0fa:a5cb:cec7] | 80, 443, 8080 | 3 |
| [2606:4700:3015:fa1:b5b8:31e2:1f22:833f] | 80, 443, 8080 | 3 |
| [2606:4700:8d95:f1f5:272c:bcea:eccd:6e7e] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:2bdb:1d36:416b:8de3:3d8e] | 80, 443, 8080 | 3 |
| [2606:4700:9768:b85:6d2d:f0fa:a5cb:cec7] | 80, 443, 8080 | 3 |
| [2606:4700:3015:fa1:b5b8:31e2:1f22:833f] | 80, 443, 8080 | 3 |
| [2606:4700:3015:7b:e27:807a:cdc8:f1e8] | 80, 443, 8080 | 5 |
| [2606:4700:3015:7b:e27:807a:cdc8:f1e8] | 80, 443, 8080 | 5 |
| [2606:4700:3015:7b:e27:807a:cdc8:f1e8] | 80, 443, 8080 | 5 |

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
