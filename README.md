# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-05 01:17:49 +0330

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
| 198.41.209.159 | 80, 443, 8080 | 54 |
| 198.41.208.32 | 80, 443, 8080 | 54 |
| 198.41.209.32 | 80, 443, 8080 | 54 |
| 198.41.209.159 | 80, 443, 8080 | 54 |
| 198.41.208.32 | 80, 443, 8080 | 54 |
| 198.41.209.32 | 80, 443, 8080 | 54 |
| 198.41.208.5 | 80, 443, 8080 | 55 |
| 198.41.209.188 | 80, 443, 8080 | 55 |
| 198.41.208.5 | 80, 443, 8080 | 55 |
| 198.41.209.188 | 80, 443, 8080 | 55 |
| 162.159.36.201 | 80, 443, 8080 | 76 |
| 104.18.88.92 | 80, 443, 8080 | 139 |
| 162.159.247.117 | 80, 443, 8080 | 139 |
| 104.19.239.85 | 80, 443, 8080 | 141 |
| 104.16.79.247 | 80, 443, 8080 | 149 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de7:da5e:de56:e3a9:72e:382d] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:59c4:1fc8:d314:21bd:572c] | 80, 443, 8080 | 3 |
| [2606:4700:10f:147e:66ad:5bfd:18f5:9b5b] | 80, 443, 8080 | 3 |
| [2606:4700:10f:c414:da65:bdfe:ceb6:6efe] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:ab27:4488:101:582a:859c] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:da5e:de56:e3a9:72e:382d] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:59c4:1fc8:d314:21bd:572c] | 80, 443, 8080 | 3 |
| [2606:4700:10f:147e:66ad:5bfd:18f5:9b5b] | 80, 443, 8080 | 3 |
| [2606:4700:10f:c414:da65:bdfe:ceb6:6efe] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:ab27:4488:101:582a:859c] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:da5e:de56:e3a9:72e:382d] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:59c4:1fc8:d314:21bd:572c] | 80, 443, 8080 | 3 |
| [2606:4700:10f:147e:66ad:5bfd:18f5:9b5b] | 80, 443, 8080 | 3 |
| [2606:4700:10f:c414:da65:bdfe:ceb6:6efe] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:ab27:4488:101:582a:859c] | 80, 443, 8080 | 3 |

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
