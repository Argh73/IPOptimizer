# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-26 02:53:47 +0330

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
| 198.41.208.40 | 80, 443, 8080 | 46 |
| 198.41.208.40 | 80, 443, 8080 | 46 |
| 198.41.208.71 | 80, 443, 8080 | 53 |
| 198.41.208.71 | 80, 443, 8080 | 53 |
| 198.41.208.158 | 80, 443, 8080 | 57 |
| 198.41.208.158 | 80, 443, 8080 | 57 |
| 198.41.208.100 | 80, 443, 8080 | 117 |
| 198.41.208.100 | 80, 443, 8080 | 117 |
| 104.19.96.63 | 80, 443, 8080 | 140 |
| 104.19.93.16 | 80, 443, 8080 | 140 |
| 104.19.118.154 | 80, 443, 8080 | 141 |
| 104.19.240.230 | 80, 443, 8080 | 141 |
| 104.18.141.152 | 80, 443, 8080 | 142 |
| 162.159.153.98 | 80, 443, 8080 | 163 |
| 162.159.153.98 | 80, 443, 8080 | 163 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:4409:734b:8cb0:af74:537a:3a34] | 80, 443, 8080 | 3 |
| [2606:4700:8392:2e0b:1606:bf30:7323:e8d9] | 80, 443, 8080 | 3 |
| [2606:4700:8392:fa16:805:8ad1:77a2:87cc] | 80, 443, 8080 | 3 |
| [2606:4700:9643:93be:2912:52e2:ff9e:2481] | 80, 443, 8080 | 3 |
| [2606:4700:4409:734b:8cb0:af74:537a:3a34] | 80, 443, 8080 | 3 |
| [2606:4700:8392:2e0b:1606:bf30:7323:e8d9] | 80, 443, 8080 | 3 |
| [2606:4700:8392:fa16:805:8ad1:77a2:87cc] | 80, 443, 8080 | 3 |
| [2606:4700:9643:93be:2912:52e2:ff9e:2481] | 80, 443, 8080 | 3 |
| [2606:4700:4409:734b:8cb0:af74:537a:3a34] | 80, 443, 8080 | 3 |
| [2606:4700:8392:2e0b:1606:bf30:7323:e8d9] | 80, 443, 8080 | 3 |
| [2606:4700:8392:fa16:805:8ad1:77a2:87cc] | 80, 443, 8080 | 3 |
| [2606:4700:9643:93be:2912:52e2:ff9e:2481] | 80, 443, 8080 | 3 |
| [2606:4700:83b1:df36:df9f:b07a:d590:9dcb] | 80, 443, 8080 | 169 |
| [2606:4700:83b1:df36:df9f:b07a:d590:9dcb] | 80, 443, 8080 | 169 |
| [2606:4700:83b1:df36:df9f:b07a:d590:9dcb] | 80, 443, 8080 | 169 |

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
