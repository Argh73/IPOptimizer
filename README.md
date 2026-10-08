# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-08 17:21:51 +0330

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
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.208.142 | 80, 443, 8080 | 69 |
| 198.41.208.69 | 80, 443, 8080 | 74 |
| 198.41.209.34 | 80, 443, 8080 | 87 |
| 198.41.209.40 | 80, 443, 8080 | 101 |
| 172.67.149.247 | 80, 443, 8080 | 138 |
| 104.19.139.156 | 80, 443, 8080 | 143 |
| 104.19.121.0 | 80, 443, 8080 | 143 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.16.105.234 | 80, 443, 8080 | 148 |
| 104.19.9.192 | 80, 443, 8080 | 148 |
| 104.18.230.114 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de7:ce39:d95c:ee0c:fcd:28c3] | 80, 443, 8080 | 3 |
| [2606:4700:9a95:d6e9:ad9c:6a64:2b23:8640] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:ce39:d95c:ee0c:fcd:28c3] | 80, 443, 8080 | 3 |
| [2606:4700:9a95:d6e9:ad9c:6a64:2b23:8640] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:ce39:d95c:ee0c:fcd:28c3] | 80, 443, 8080 | 3 |
| [2606:4700:9a95:d6e9:ad9c:6a64:2b23:8640] | 80, 443, 8080 | 3 |
| [2606:4700:9aee:92e7:4d8c:5d5c:92f7:b4c2] | 80, 443, 8080 | 4 |
| [2606:4700:9aee:d2f1:2084:4183:b583:b72a] | 80, 443, 8080 | 4 |
| [2606:4700:8dee:a668:c5e5:df7d:7496:5b] | 80, 443, 8080 | 4 |
| [2606:4700:9aee:92e7:4d8c:5d5c:92f7:b4c2] | 80, 443, 8080 | 4 |
| [2606:4700:9aee:d2f1:2084:4183:b583:b72a] | 80, 443, 8080 | 4 |
| [2606:4700:8dee:a668:c5e5:df7d:7496:5b] | 80, 443, 8080 | 4 |
| [2606:4700:9aee:92e7:4d8c:5d5c:92f7:b4c2] | 80, 443, 8080 | 4 |
| [2606:4700:9aee:d2f1:2084:4183:b583:b72a] | 80, 443, 8080 | 4 |
| [2606:4700:8dee:a668:c5e5:df7d:7496:5b] | 80, 443, 8080 | 4 |

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
