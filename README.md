# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-07 01:07:17 +0330

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
| 198.41.222.53 | 80, 443, 8080 | 71 |
| 198.41.211.129 | 80, 443, 8080 | 71 |
| 198.41.211.93 | 80, 443, 8080 | 71 |
| 198.41.222.53 | 80, 443, 8080 | 71 |
| 198.41.211.129 | 80, 443, 8080 | 71 |
| 198.41.211.93 | 80, 443, 8080 | 71 |
| 198.41.222.53 | 80, 443, 8080 | 71 |
| 198.41.211.129 | 80, 443, 8080 | 71 |
| 198.41.211.93 | 80, 443, 8080 | 71 |
| 198.41.223.157 | 80, 443, 8080 | 105 |
| 198.41.223.157 | 80, 443, 8080 | 105 |
| 198.41.223.157 | 80, 443, 8080 | 105 |
| 104.19.120.215 | 80, 443, 8080 | 133 |
| 104.19.120.215 | 80, 443, 8080 | 133 |
| 104.19.120.215 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:99e2:6662:cc54:2d41:78f6:326d] | 80, 443, 8080 | 0 |
| [2606:4700:99e2:6662:cc54:2d41:78f6:326d] | 80, 443, 8080 | 0 |
| [2606:4700:99e2:6662:cc54:2d41:78f6:326d] | 80, 443, 8080 | 0 |
| [2606:4700:9c69:4843:26bd:b1b6:2929:a615] | 80, 443, 8080 | 3 |
| [2606:4700:964a:20b6:10bf:da0:fdc5:9353] | 80, 443, 8080 | 3 |
| [2606:4700:3055:7fd7:da4f:200c:ec5c:3ff1] | 80, 443, 8080 | 3 |
| [2606:4700:9c69:4843:26bd:b1b6:2929:a615] | 80, 443, 8080 | 3 |
| [2606:4700:964a:20b6:10bf:da0:fdc5:9353] | 80, 443, 8080 | 3 |
| [2606:4700:3055:7fd7:da4f:200c:ec5c:3ff1] | 80, 443, 8080 | 3 |
| [2606:4700:9c69:4843:26bd:b1b6:2929:a615] | 80, 443, 8080 | 3 |
| [2606:4700:964a:20b6:10bf:da0:fdc5:9353] | 80, 443, 8080 | 3 |
| [2606:4700:3055:7fd7:da4f:200c:ec5c:3ff1] | 80, 443, 8080 | 3 |
| [2606:4700:3055:9421:304f:20a8:8b6a:8dcc] | 80, 443, 8080 | 12 |
| [2606:4700:3055:9421:304f:20a8:8b6a:8dcc] | 80, 443, 8080 | 12 |
| [2606:4700:3055:9421:304f:20a8:8b6a:8dcc] | 80, 443, 8080 | 12 |

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
