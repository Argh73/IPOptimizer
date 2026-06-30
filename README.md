# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-30 13:37:03 +0330

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
| 198.41.208.202 | 80, 443, 8080 | 52 |
| 198.41.208.202 | 80, 443, 8080 | 52 |
| 198.41.209.8 | 80, 443, 8080 | 54 |
| 198.41.209.8 | 80, 443, 8080 | 54 |
| 162.159.36.166 | 80, 443, 8080 | 72 |
| 198.41.222.102 | 80, 443, 8080 | 81 |
| 104.16.196.127 | 80, 443, 8080 | 130 |
| 104.16.136.243 | 80, 443, 8080 | 132 |
| 104.19.166.245 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:964d:132f:5f6d:c52b:488a:b351] | 80, 443, 8080 | 3 |
| [2606:4700:8d9c:88a3:89d8:b5f4:334d:10f8] | 80, 443, 8080 | 3 |
| [2606:4700:8d9c:8712:fcc:9833:debb:6b51] | 80, 443, 8080 | 3 |
| [2606:4700:9a6e:b4f4:cd73:355d:6718:eacc] | 80, 443, 8080 | 3 |
| [2606:4700:964d:132f:5f6d:c52b:488a:b351] | 80, 443, 8080 | 3 |
| [2606:4700:8d9c:88a3:89d8:b5f4:334d:10f8] | 80, 443, 8080 | 3 |
| [2606:4700:8d9c:8712:fcc:9833:debb:6b51] | 80, 443, 8080 | 3 |
| [2606:4700:9a6e:b4f4:cd73:355d:6718:eacc] | 80, 443, 8080 | 3 |
| [2606:4700:964d:132f:5f6d:c52b:488a:b351] | 80, 443, 8080 | 3 |
| [2606:4700:8d9c:88a3:89d8:b5f4:334d:10f8] | 80, 443, 8080 | 3 |
| [2606:4700:8d9c:8712:fcc:9833:debb:6b51] | 80, 443, 8080 | 3 |
| [2606:4700:9a6e:b4f4:cd73:355d:6718:eacc] | 80, 443, 8080 | 3 |
| [2606:4700:4403:12d1:32c3:b74d:189b:dcc] | 80, 443, 8080 | 13 |
| [2606:4700:4403:12d1:32c3:b74d:189b:dcc] | 80, 443, 8080 | 13 |
| [2606:4700:4403:12d1:32c3:b74d:189b:dcc] | 80, 443, 8080 | 13 |

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
