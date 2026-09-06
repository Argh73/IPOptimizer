# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-07 01:43:04 +0330

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
| 198.41.209.102 | 80, 443, 8080 | 51 |
| 198.41.209.102 | 80, 443, 8080 | 51 |
| 198.41.209.13 | 80, 443, 8080 | 55 |
| 198.41.209.13 | 80, 443, 8080 | 55 |
| 198.41.222.178 | 80, 443, 8080 | 64 |
| 198.41.209.150 | 80, 443, 8080 | 89 |
| 198.41.209.150 | 80, 443, 8080 | 89 |
| 198.41.209.207 | 80, 443, 8080 | 117 |
| 198.41.209.207 | 80, 443, 8080 | 117 |
| 198.41.209.96 | 80, 443, 8080 | 136 |
| 198.41.209.96 | 80, 443, 8080 | 136 |
| 104.17.186.250 | 80, 443, 8080 | 138 |
| 104.17.6.73 | 80, 443, 8080 | 139 |
| 104.17.208.62 | 80, 443, 8080 | 144 |
| 104.25.6.126 | 80, 443, 8080 | 146 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c6a:b968:c3bf:9c8:7c8:78df] | 80, 443, 8080 | 3 |
| [2606:4700:9760:8a4:c226:31bb:5be7:8be] | 80, 443, 8080 | 3 |
| [2606:4700:9c6a:b968:c3bf:9c8:7c8:78df] | 80, 443, 8080 | 3 |
| [2606:4700:9760:8a4:c226:31bb:5be7:8be] | 80, 443, 8080 | 3 |
| [2606:4700:9c6a:b968:c3bf:9c8:7c8:78df] | 80, 443, 8080 | 3 |
| [2606:4700:9760:8a4:c226:31bb:5be7:8be] | 80, 443, 8080 | 3 |
| [2606:4700:9760:f424:d336:7061:1200:4d69] | 80, 443, 8080 | 5 |
| [2606:4700:9760:f424:d336:7061:1200:4d69] | 80, 443, 8080 | 5 |
| [2606:4700:9760:f424:d336:7061:1200:4d69] | 80, 443, 8080 | 5 |
| [2606:4700:8ca4:1852:4db4:4dd7:3989:4456] | 80, 443, 8080 | 125 |
| [2606:4700:8ca4:1852:4db4:4dd7:3989:4456] | 80, 443, 8080 | 125 |
| [2606:4700:8ca4:1852:4db4:4dd7:3989:4456] | 80, 443, 8080 | 125 |
| [2606:4700:8ca4:981f:947c:a7ed:c57a:c5c7] | 80, 443, 8080 | 138 |
| [2606:4700:8ca4:981f:947c:a7ed:c57a:c5c7] | 80, 443, 8080 | 138 |
| [2606:4700:8ca4:981f:947c:a7ed:c57a:c5c7] | 80, 443, 8080 | 138 |

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
