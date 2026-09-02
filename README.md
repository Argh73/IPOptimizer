# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-03 02:15:18 +0330

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
| 104.16.100.139 | 80, 443, 8080 | 139 |
| 104.16.100.139 | 80, 443, 8080 | 139 |
| 104.16.100.139 | 80, 443, 8080 | 139 |
| 104.16.10.10 | 80, 443, 8080 | 140 |
| 104.16.10.10 | 80, 443, 8080 | 140 |
| 104.16.10.10 | 80, 443, 8080 | 140 |
| 104.16.111.220 | 80, 443, 8080 | 142 |
| 104.16.111.220 | 80, 443, 8080 | 142 |
| 104.16.111.220 | 80, 443, 8080 | 142 |
| 104.16.120.53 | 80, 443, 8080 | 144 |
| 104.16.120.53 | 80, 443, 8080 | 144 |
| 104.16.120.53 | 80, 443, 8080 | 144 |
| 104.16.111.90 | 80, 443, 8080 | 145 |
| 104.16.111.90 | 80, 443, 8080 | 145 |
| 104.16.111.90 | 80, 443, 8080 | 145 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:20:5f8e:b994:8e4b:2b44:5c26] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:e5b8:cea7:9b19:f83b:7063] | 80, 443, 8080 | 3 |
| [2606:4700:20:5f8e:b994:8e4b:2b44:5c26] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:e5b8:cea7:9b19:f83b:7063] | 80, 443, 8080 | 3 |
| [2606:4700:20:5f8e:b994:8e4b:2b44:5c26] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:e5b8:cea7:9b19:f83b:7063] | 80, 443, 8080 | 3 |
| [2606:4700:3017:6ceb:35c6:3b4c:6b1d:9a19] | 80, 443, 8080 | 4 |
| [2606:4700:3017:1b8f:ff03:4f54:c57b:9c1f] | 80, 443, 8080 | 4 |
| [2606:4700:3017:6ceb:35c6:3b4c:6b1d:9a19] | 80, 443, 8080 | 4 |
| [2606:4700:3017:1b8f:ff03:4f54:c57b:9c1f] | 80, 443, 8080 | 4 |
| [2606:4700:3017:6ceb:35c6:3b4c:6b1d:9a19] | 80, 443, 8080 | 4 |
| [2606:4700:3017:1b8f:ff03:4f54:c57b:9c1f] | 80, 443, 8080 | 4 |
| [2606:4700:20:99df:d200:aa98:9894:5ca9] | 80, 443, 8080 | 13 |
| [2606:4700:20:99df:d200:aa98:9894:5ca9] | 80, 443, 8080 | 13 |
| [2606:4700:20:99df:d200:aa98:9894:5ca9] | 80, 443, 8080 | 13 |

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
