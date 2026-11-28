# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-28 19:15:06 +0330

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
| 104.19.112.219 | 80, 443, 8080 | 142 |
| 104.17.128.201 | 80, 443, 8080 | 142 |
| 104.19.6.255 | 80, 443, 8080 | 142 |
| 104.19.81.106 | 80, 443, 8080 | 142 |
| 104.19.59.0 | 80, 443, 8080 | 142 |
| 162.159.160.235 | 80, 443, 8080 | 154 |
| 162.159.160.235 | 80, 443, 8080 | 154 |
| 162.159.128.34 | 80, 443, 8080 | 161 |
| 162.159.128.113 | 80, 443, 8080 | 161 |
| 162.159.128.34 | 80, 443, 8080 | 161 |
| 162.159.128.113 | 80, 443, 8080 | 161 |
| 162.159.128.41 | 80, 443, 8080 | 162 |
| 162.159.128.90 | 80, 443, 8080 | 162 |
| 162.159.128.41 | 80, 443, 8080 | 162 |
| 162.159.128.90 | 80, 443, 8080 | 162 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de8:f21f:4e1b:e7df:d343:1725] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:db83:3cc8:c95d:6d8e:f6de] | 80, 443, 8080 | 3 |
| [2606:4700:8de8:14d2:ab29:ced6:bbe7:6304] | 80, 443, 8080 | 3 |
| [2606:4700:83bc:1c0c:1481:c678:72bc:2570] | 80, 443, 8080 | 3 |
| [2606:4700:8de8:f21f:4e1b:e7df:d343:1725] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:db83:3cc8:c95d:6d8e:f6de] | 80, 443, 8080 | 3 |
| [2606:4700:8de8:14d2:ab29:ced6:bbe7:6304] | 80, 443, 8080 | 3 |
| [2606:4700:83bc:1c0c:1481:c678:72bc:2570] | 80, 443, 8080 | 3 |
| [2606:4700:8de8:f21f:4e1b:e7df:d343:1725] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:db83:3cc8:c95d:6d8e:f6de] | 80, 443, 8080 | 3 |
| [2606:4700:8de8:14d2:ab29:ced6:bbe7:6304] | 80, 443, 8080 | 3 |
| [2606:4700:83bc:1c0c:1481:c678:72bc:2570] | 80, 443, 8080 | 3 |
| [2606:4700:3011:5bcc:218e:e064:8d60:5f41] | 80, 443, 8080 | 13 |
| [2606:4700:3011:5bcc:218e:e064:8d60:5f41] | 80, 443, 8080 | 13 |
| [2606:4700:3011:5bcc:218e:e064:8d60:5f41] | 80, 443, 8080 | 13 |

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
