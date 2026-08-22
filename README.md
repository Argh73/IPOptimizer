# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-23 00:17:49 +0330

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
| 104.16.176.73 | 80, 443, 8080 | 130 |
| 104.18.241.242 | 80, 443, 8080 | 131 |
| 104.19.119.49 | 80, 443, 8080 | 139 |
| 104.17.61.199 | 80, 443, 8080 | 141 |
| 104.17.70.248 | 80, 443, 8080 | 141 |
| 162.159.160.16 | 80, 443, 8080 | 151 |
| 162.159.160.16 | 80, 443, 8080 | 151 |
| 162.159.137.182 | 80, 443, 8080 | 163 |
| 162.159.135.188 | 80, 443, 8080 | 163 |
| 162.159.137.182 | 80, 443, 8080 | 163 |
| 162.159.135.188 | 80, 443, 8080 | 163 |
| 162.159.135.34 | 80, 443, 8080 | 165 |
| 162.159.135.34 | 80, 443, 8080 | 165 |
| 162.159.138.248 | 80, 443, 8080 | 166 |
| 162.159.138.248 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d91:ef67:aa58:2a3b:dc80:45ad] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:beb6:b0ab:257f:2113:bca7] | 80, 443, 8080 | 3 |
| [2606:4700:14:89ec:b977:5a6c:7af7:2ccb] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:1651:1cf7:4b15:585a:a0fc] | 80, 443, 8080 | 3 |
| [2606:4700:8d91:ef67:aa58:2a3b:dc80:45ad] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:beb6:b0ab:257f:2113:bca7] | 80, 443, 8080 | 3 |
| [2606:4700:14:89ec:b977:5a6c:7af7:2ccb] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:1651:1cf7:4b15:585a:a0fc] | 80, 443, 8080 | 3 |
| [2606:4700:8d91:ef67:aa58:2a3b:dc80:45ad] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:beb6:b0ab:257f:2113:bca7] | 80, 443, 8080 | 3 |
| [2606:4700:14:89ec:b977:5a6c:7af7:2ccb] | 80, 443, 8080 | 3 |
| [2606:4700:9c67:1651:1cf7:4b15:585a:a0fc] | 80, 443, 8080 | 3 |
| [2606:4700:1a:927:dddd:8edb:9d07:cd71] | 80, 443, 8080 | 12 |
| [2606:4700:1a:927:dddd:8edb:9d07:cd71] | 80, 443, 8080 | 12 |
| [2606:4700:1a:927:dddd:8edb:9d07:cd71] | 80, 443, 8080 | 12 |

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
