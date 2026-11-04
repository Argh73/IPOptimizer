# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-04 04:15:55 +0330

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
| 198.41.209.3 | 80, 443, 8080 | 48 |
| 198.41.209.3 | 80, 443, 8080 | 48 |
| 198.41.208.29 | 80, 443, 8080 | 50 |
| 198.41.208.29 | 80, 443, 8080 | 50 |
| 198.41.208.10 | 80, 443, 8080 | 54 |
| 198.41.208.10 | 80, 443, 8080 | 54 |
| 198.41.208.70 | 80, 443, 8080 | 68 |
| 198.41.208.70 | 80, 443, 8080 | 68 |
| 198.41.208.222 | 80, 443, 8080 | 94 |
| 198.41.208.222 | 80, 443, 8080 | 94 |
| 104.17.135.87 | 80, 443, 8080 | 140 |
| 104.19.1.28 | 80, 443, 8080 | 140 |
| 172.64.79.238 | 80, 443, 8080 | 147 |
| 172.64.79.198 | 80, 443, 8080 | 147 |
| 104.19.68.134 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3001:6b04:8155:5fc6:e1b3:835] | 80, 443, 8080 | 3 |
| [2606:4700:9768:dab4:cd6:57f1:76cb:a107] | 80, 443, 8080 | 3 |
| [2606:4700:3001:6b04:8155:5fc6:e1b3:835] | 80, 443, 8080 | 3 |
| [2606:4700:9768:dab4:cd6:57f1:76cb:a107] | 80, 443, 8080 | 3 |
| [2606:4700:3001:6b04:8155:5fc6:e1b3:835] | 80, 443, 8080 | 3 |
| [2606:4700:9768:dab4:cd6:57f1:76cb:a107] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:f6c8:9167:8d36:b895:3e46] | 80, 443, 8080 | 4 |
| [2606:4700:9c6d:f6c8:9167:8d36:b895:3e46] | 80, 443, 8080 | 4 |
| [2606:4700:9c6d:f6c8:9167:8d36:b895:3e46] | 80, 443, 8080 | 4 |
| [2606:4700:90c5:5e55:b8cb:5d9e:1777:74d] | 80, 443, 8080 | 164 |
| [2606:4700:90c5:5e55:b8cb:5d9e:1777:74d] | 80, 443, 8080 | 164 |
| [2606:4700:90c5:5e55:b8cb:5d9e:1777:74d] | 80, 443, 8080 | 164 |
| [2606:4700:90c5:bad6:b917:8385:11a:d131] | 80, 443, 8080 | 166 |
| [2606:4700:90c5:bad6:b917:8385:11a:d131] | 80, 443, 8080 | 166 |
| [2606:4700:90c5:bad6:b917:8385:11a:d131] | 80, 443, 8080 | 166 |

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
