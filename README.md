# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-10 02:10:30 +0330

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
| 198.41.208.44 | 80, 443, 8080 | 48 |
| 198.41.209.160 | 80, 443, 8080 | 48 |
| 198.41.208.44 | 80, 443, 8080 | 48 |
| 198.41.209.160 | 80, 443, 8080 | 48 |
| 198.41.209.173 | 80, 443, 8080 | 51 |
| 198.41.209.173 | 80, 443, 8080 | 51 |
| 198.41.208.189 | 80, 443, 8080 | 60 |
| 198.41.208.189 | 80, 443, 8080 | 60 |
| 198.41.208.193 | 80, 443, 8080 | 72 |
| 198.41.208.193 | 80, 443, 8080 | 72 |
| 198.41.222.38 | 80, 443, 8080 | 75 |
| 198.41.211.96 | 80, 443, 8080 | 86 |
| 104.16.2.195 | 80, 443, 8080 | 138 |
| 104.16.134.142 | 80, 443, 8080 | 139 |
| 104.18.108.175 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8cae:fa1:daa2:b8e0:5aa1:9843] | 80, 443, 8080 | 3 |
| [2606:4700:8d97:b153:6ab4:9c51:9571:6d6d] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:fa1:daa2:b8e0:5aa1:9843] | 80, 443, 8080 | 3 |
| [2606:4700:8d97:b153:6ab4:9c51:9571:6d6d] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:fa1:daa2:b8e0:5aa1:9843] | 80, 443, 8080 | 3 |
| [2606:4700:8d97:b153:6ab4:9c51:9571:6d6d] | 80, 443, 8080 | 3 |
| [2606:4700:8d97:c2c5:3b5:94b9:5c06:d8af] | 80, 443, 8080 | 4 |
| [2606:4700:8cae:b939:e777:5dd:91f4:e70] | 80, 443, 8080 | 4 |
| [2606:4700:8d97:c2c5:3b5:94b9:5c06:d8af] | 80, 443, 8080 | 4 |
| [2606:4700:8cae:b939:e777:5dd:91f4:e70] | 80, 443, 8080 | 4 |
| [2606:4700:8d97:c2c5:3b5:94b9:5c06:d8af] | 80, 443, 8080 | 4 |
| [2606:4700:8cae:b939:e777:5dd:91f4:e70] | 80, 443, 8080 | 4 |
| [2606:4700:1e:55ec:65d2:16ef:3d44:27eb] | 80, 443, 8080 | 13 |
| [2606:4700:1e:55ec:65d2:16ef:3d44:27eb] | 80, 443, 8080 | 13 |
| [2606:4700:1e:55ec:65d2:16ef:3d44:27eb] | 80, 443, 8080 | 13 |

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
