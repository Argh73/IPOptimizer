# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-22 15:44:46 +0330

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
| 198.41.209.96 | 80, 443, 8080 | 54 |
| 198.41.209.96 | 80, 443, 8080 | 54 |
| 198.41.209.190 | 80, 443, 8080 | 56 |
| 198.41.209.190 | 80, 443, 8080 | 56 |
| 172.67.155.98 | 80, 443, 8080 | 132 |
| 172.67.155.98 | 80, 443, 8080 | 132 |
| 172.67.64.114 | 80, 443, 8080 | 134 |
| 172.67.64.114 | 80, 443, 8080 | 134 |
| 172.67.74.7 | 80, 443, 8080 | 137 |
| 172.67.74.7 | 80, 443, 8080 | 137 |
| 104.17.31.246 | 80, 443, 8080 | 147 |
| 104.18.78.108 | 80, 443, 8080 | 148 |
| 104.17.249.145 | 80, 443, 8080 | 148 |
| 104.16.151.222 | 80, 443, 8080 | 149 |
| 104.16.217.87 | 80, 443, 8080 | 149 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9769:8e2:e8e8:9423:ec8e:31e1] | 80, 443, 8080 | 3 |
| [2606:4700:91b1:97fd:30d7:d8c8:9c6e:a32f] | 80, 443, 8080 | 3 |
| [2606:4700:91b1:d3c7:417f:4b88:7ab1:75c] | 80, 443, 8080 | 3 |
| [2606:4700:9c6e:bbb4:9e36:d83b:abf6:2e68] | 80, 443, 8080 | 3 |
| [2606:4700:9769:8e2:e8e8:9423:ec8e:31e1] | 80, 443, 8080 | 3 |
| [2606:4700:91b1:97fd:30d7:d8c8:9c6e:a32f] | 80, 443, 8080 | 3 |
| [2606:4700:91b1:d3c7:417f:4b88:7ab1:75c] | 80, 443, 8080 | 3 |
| [2606:4700:9c6e:bbb4:9e36:d83b:abf6:2e68] | 80, 443, 8080 | 3 |
| [2606:4700:9769:8e2:e8e8:9423:ec8e:31e1] | 80, 443, 8080 | 3 |
| [2606:4700:91b1:97fd:30d7:d8c8:9c6e:a32f] | 80, 443, 8080 | 3 |
| [2606:4700:91b1:d3c7:417f:4b88:7ab1:75c] | 80, 443, 8080 | 3 |
| [2606:4700:9c6e:bbb4:9e36:d83b:abf6:2e68] | 80, 443, 8080 | 3 |
| [2606:4700:9648:36f:63ee:d9e1:f2de:880a] | 80, 443, 8080 | 4 |
| [2606:4700:9648:36f:63ee:d9e1:f2de:880a] | 80, 443, 8080 | 4 |
| [2606:4700:9648:36f:63ee:d9e1:f2de:880a] | 80, 443, 8080 | 4 |

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
