# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-28 12:47:20 +0330

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
| 198.41.209.50 | 80, 443, 8080 | 51 |
| 198.41.209.50 | 80, 443, 8080 | 51 |
| 198.41.209.72 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.209.23 | 80, 443, 8080 | 54 |
| 198.41.209.72 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.209.23 | 80, 443, 8080 | 54 |
| 198.41.208.106 | 80, 443, 8080 | 57 |
| 198.41.208.106 | 80, 443, 8080 | 57 |
| 104.19.132.105 | 80, 443, 8080 | 143 |
| 141.101.114.113 | 80, 443, 8080 | 151 |
| 104.21.2.104 | 80, 443, 8080 | 161 |
| 104.25.177.142 | 80, 443, 8080 | 166 |
| 104.24.83.3 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:13d:a71a:258a:8096:2172:6480] | 80, 443, 8080 | 0 |
| [2606:4700:91b6:1651:9fc2:cd5b:812a:8d6a] | 80, 443, 8080 | 0 |
| [2606:4700:134:7a27:65c:ece3:4e71:14a5] | 80, 443, 8080 | 0 |
| [2606:4700:13d:a71a:258a:8096:2172:6480] | 80, 443, 8080 | 0 |
| [2606:4700:91b6:1651:9fc2:cd5b:812a:8d6a] | 80, 443, 8080 | 0 |
| [2606:4700:134:7a27:65c:ece3:4e71:14a5] | 80, 443, 8080 | 0 |
| [2606:4700:13d:a71a:258a:8096:2172:6480] | 80, 443, 8080 | 0 |
| [2606:4700:91b6:1651:9fc2:cd5b:812a:8d6a] | 80, 443, 8080 | 0 |
| [2606:4700:134:7a27:65c:ece3:4e71:14a5] | 80, 443, 8080 | 0 |
| [2606:4700:134:f2d4:5f89:3fa9:9f1a:497c] | 80, 443, 8080 | 1 |
| [2606:4700:13d:c2c4:a4d9:69b:1bf3:a382] | 80, 443, 8080 | 1 |
| [2606:4700:134:f2d4:5f89:3fa9:9f1a:497c] | 80, 443, 8080 | 1 |
| [2606:4700:13d:c2c4:a4d9:69b:1bf3:a382] | 80, 443, 8080 | 1 |
| [2606:4700:134:f2d4:5f89:3fa9:9f1a:497c] | 80, 443, 8080 | 1 |
| [2606:4700:13d:c2c4:a4d9:69b:1bf3:a382] | 80, 443, 8080 | 1 |

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
