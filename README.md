# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-13 04:49:20 +0330

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
| 198.41.209.184 | 80, 443, 8080 | 48 |
| 198.41.209.184 | 80, 443, 8080 | 48 |
| 198.41.208.53 | 80, 443, 8080 | 49 |
| 198.41.208.53 | 80, 443, 8080 | 49 |
| 198.41.208.151 | 80, 443, 8080 | 52 |
| 198.41.208.120 | 80, 443, 8080 | 52 |
| 198.41.208.151 | 80, 443, 8080 | 52 |
| 198.41.208.120 | 80, 443, 8080 | 52 |
| 198.41.208.138 | 80, 443, 8080 | 60 |
| 198.41.208.138 | 80, 443, 8080 | 60 |
| 104.19.73.121 | 80, 443, 8080 | 143 |
| 104.19.125.145 | 80, 443, 8080 | 144 |
| 104.19.51.119 | 80, 443, 8080 | 152 |
| 172.67.142.42 | 80, 443, 8080 | 157 |
| 104.20.62.15 | 80, 443, 8080 | 170 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d99:a51a:a363:5b78:3615:2da4] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:cccf:fed9:dc8c:1b4f:ce79] | 80, 443, 8080 | 3 |
| [2606:4700:9ad3:afb1:570e:9057:3bf0:e381] | 80, 443, 8080 | 3 |
| [2606:4700:9644:275c:ee3:bb10:1f9b:7bc8] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:a51a:a363:5b78:3615:2da4] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:cccf:fed9:dc8c:1b4f:ce79] | 80, 443, 8080 | 3 |
| [2606:4700:9ad3:afb1:570e:9057:3bf0:e381] | 80, 443, 8080 | 3 |
| [2606:4700:9644:275c:ee3:bb10:1f9b:7bc8] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:a51a:a363:5b78:3615:2da4] | 80, 443, 8080 | 3 |
| [2606:4700:8d99:cccf:fed9:dc8c:1b4f:ce79] | 80, 443, 8080 | 3 |
| [2606:4700:9ad3:afb1:570e:9057:3bf0:e381] | 80, 443, 8080 | 3 |
| [2606:4700:9644:275c:ee3:bb10:1f9b:7bc8] | 80, 443, 8080 | 3 |
| [2606:4700:4404:c47e:e246:cc65:f7ff:8461] | 80, 443, 8080 | 12 |
| [2606:4700:4404:c47e:e246:cc65:f7ff:8461] | 80, 443, 8080 | 12 |
| [2606:4700:4404:c47e:e246:cc65:f7ff:8461] | 80, 443, 8080 | 12 |

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
