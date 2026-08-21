# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-21 10:53:56 +0330

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
| 104.17.41.184 | 80, 443, 8080 | 142 |
| 104.19.182.180 | 80, 443, 8080 | 142 |
| 104.17.41.184 | 80, 443, 8080 | 142 |
| 104.19.182.180 | 80, 443, 8080 | 142 |
| 104.17.41.184 | 80, 443, 8080 | 142 |
| 104.19.182.180 | 80, 443, 8080 | 142 |
| 104.16.22.197 | 80, 443, 8080 | 143 |
| 104.18.217.24 | 80, 443, 8080 | 143 |
| 104.16.22.197 | 80, 443, 8080 | 143 |
| 104.18.217.24 | 80, 443, 8080 | 143 |
| 104.16.22.197 | 80, 443, 8080 | 143 |
| 104.18.217.24 | 80, 443, 8080 | 143 |
| 104.18.88.73 | 80, 443, 8080 | 144 |
| 104.18.88.73 | 80, 443, 8080 | 144 |
| 104.18.88.73 | 80, 443, 8080 | 144 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3009:da17:54d2:fddb:97f3:8154] | 80, 443, 8080 | 0 |
| [2606:4700:8de4:a037:6976:a8fe:7f74:65] | 80, 443, 8080 | 0 |
| [2606:4700:3009:da17:54d2:fddb:97f3:8154] | 80, 443, 8080 | 0 |
| [2606:4700:8de4:a037:6976:a8fe:7f74:65] | 80, 443, 8080 | 0 |
| [2606:4700:3009:da17:54d2:fddb:97f3:8154] | 80, 443, 8080 | 0 |
| [2606:4700:8de4:a037:6976:a8fe:7f74:65] | 80, 443, 8080 | 0 |
| [2606:4700:3033:72c7:7cc9:49f6:5650:367e] | 80, 443, 8080 | 1 |
| [2606:4700:9c65:c0b4:b82:c415:19bd:ad94] | 80, 443, 8080 | 1 |
| [2606:4700:3009:38a9:a4f4:3d03:d435:d95] | 80, 443, 8080 | 1 |
| [2606:4700:3033:72c7:7cc9:49f6:5650:367e] | 80, 443, 8080 | 1 |
| [2606:4700:9c65:c0b4:b82:c415:19bd:ad94] | 80, 443, 8080 | 1 |
| [2606:4700:3009:38a9:a4f4:3d03:d435:d95] | 80, 443, 8080 | 1 |
| [2606:4700:3033:72c7:7cc9:49f6:5650:367e] | 80, 443, 8080 | 1 |
| [2606:4700:9c65:c0b4:b82:c415:19bd:ad94] | 80, 443, 8080 | 1 |
| [2606:4700:3009:38a9:a4f4:3d03:d435:d95] | 80, 443, 8080 | 1 |

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
