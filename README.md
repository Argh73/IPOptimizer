# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-18 14:23:48 +0330

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
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.209.17 | 80, 443, 8080 | 53 |
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.209.17 | 80, 443, 8080 | 53 |
| 198.41.208.181 | 80, 443, 8080 | 54 |
| 198.41.208.45 | 80, 443, 8080 | 54 |
| 198.41.208.181 | 80, 443, 8080 | 54 |
| 198.41.208.45 | 80, 443, 8080 | 54 |
| 162.159.36.186 | 80, 443, 8080 | 99 |
| 172.64.92.18 | 80, 443, 8080 | 131 |
| 104.17.37.201 | 80, 443, 8080 | 142 |
| 104.16.163.202 | 80, 443, 8080 | 146 |
| 104.16.95.244 | 80, 443, 8080 | 149 |
| 172.67.70.77 | 80, 443, 8080 | 194 |
| 172.67.70.77 | 80, 443, 8080 | 194 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91b3:d3e6:39e7:9c96:b253:275b] | 80, 443, 8080 | 0 |
| [2606:4700:91b3:63c8:d0ac:5f:f0ee:f041] | 80, 443, 8080 | 0 |
| [2606:4700:8d91:491f:9e19:c54f:5339:48aa] | 80, 443, 8080 | 0 |
| [2606:4700:91b3:d3e6:39e7:9c96:b253:275b] | 80, 443, 8080 | 0 |
| [2606:4700:91b3:63c8:d0ac:5f:f0ee:f041] | 80, 443, 8080 | 0 |
| [2606:4700:8d91:491f:9e19:c54f:5339:48aa] | 80, 443, 8080 | 0 |
| [2606:4700:91b3:d3e6:39e7:9c96:b253:275b] | 80, 443, 8080 | 0 |
| [2606:4700:91b3:63c8:d0ac:5f:f0ee:f041] | 80, 443, 8080 | 0 |
| [2606:4700:8d91:491f:9e19:c54f:5339:48aa] | 80, 443, 8080 | 0 |
| [2606:4700:9a6e:58a1:67f3:4f81:ac6e:74bc] | 80, 443, 8080 | 1 |
| [2606:4700:130:7574:32a6:5eee:8f6a:449c] | 80, 443, 8080 | 1 |
| [2606:4700:9a6e:58a1:67f3:4f81:ac6e:74bc] | 80, 443, 8080 | 1 |
| [2606:4700:130:7574:32a6:5eee:8f6a:449c] | 80, 443, 8080 | 1 |
| [2606:4700:9a6e:58a1:67f3:4f81:ac6e:74bc] | 80, 443, 8080 | 1 |
| [2606:4700:130:7574:32a6:5eee:8f6a:449c] | 80, 443, 8080 | 1 |

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
