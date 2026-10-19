# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-20 03:21:06 +0330

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
| 198.41.208.86 | 80, 443, 8080 | 47 |
| 198.41.209.200 | 80, 443, 8080 | 49 |
| 198.41.209.9 | 80, 443, 8080 | 49 |
| 198.41.208.148 | 80, 443, 8080 | 50 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 172.67.165.64 | 80, 443, 8080 | 131 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.24.63.249 | 80, 443, 8080 | 162 |
| 104.25.93.58 | 80, 443, 8080 | 163 |
| 104.20.25.200 | 80, 443, 8080 | 163 |
| 104.27.11.185 | 80, 443, 8080 | 163 |
| 104.20.42.76 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9adb:55e:a56:401f:d73a:6ccc] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:6c2e:652:729a:a591:c73b] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:d9a2:78c3:9072:5c0c:7b86] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:b4c1:4273:749c:5c9d:b855] | 80, 443, 8080 | 3 |
| [2606:4700:9adb:55e:a56:401f:d73a:6ccc] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:6c2e:652:729a:a591:c73b] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:d9a2:78c3:9072:5c0c:7b86] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:b4c1:4273:749c:5c9d:b855] | 80, 443, 8080 | 3 |
| [2606:4700:9adb:55e:a56:401f:d73a:6ccc] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:6c2e:652:729a:a591:c73b] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:d9a2:78c3:9072:5c0c:7b86] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:b4c1:4273:749c:5c9d:b855] | 80, 443, 8080 | 3 |
| [2606:4700:9ade:80a:dbab:c1f0:512b:d0e9] | 80, 443, 8080 | 4 |
| [2606:4700:9ade:80a:dbab:c1f0:512b:d0e9] | 80, 443, 8080 | 4 |
| [2606:4700:9ade:80a:dbab:c1f0:512b:d0e9] | 80, 443, 8080 | 4 |

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
