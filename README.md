# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-14 16:41:26 +0330

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
| 198.41.208.91 | 80, 443, 8080 | 49 |
| 198.41.208.91 | 80, 443, 8080 | 49 |
| 198.41.209.228 | 80, 443, 8080 | 53 |
| 198.41.209.228 | 80, 443, 8080 | 53 |
| 198.41.209.157 | 80, 443, 8080 | 60 |
| 198.41.208.250 | 80, 443, 8080 | 60 |
| 198.41.209.157 | 80, 443, 8080 | 60 |
| 198.41.208.250 | 80, 443, 8080 | 60 |
| 162.159.46.22 | 80, 443, 8080 | 71 |
| 198.41.208.200 | 80, 443, 8080 | 79 |
| 198.41.208.200 | 80, 443, 8080 | 79 |
| 104.16.223.1 | 80, 443, 8080 | 141 |
| 104.17.3.134 | 80, 443, 8080 | 141 |
| 104.19.3.206 | 80, 443, 8080 | 142 |
| 104.19.55.20 | 80, 443, 8080 | 143 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ad4:5795:7bce:88fa:bece:915a] | 80, 443, 8080 | 3 |
| [2606:4700:54:46e4:b78b:c257:668f:3de6] | 80, 443, 8080 | 3 |
| [2606:4700:9ad4:60b3:7a1e:13df:1089:fa5] | 80, 443, 8080 | 3 |
| [2606:4700:9ad4:5795:7bce:88fa:bece:915a] | 80, 443, 8080 | 3 |
| [2606:4700:54:46e4:b78b:c257:668f:3de6] | 80, 443, 8080 | 3 |
| [2606:4700:9ad4:60b3:7a1e:13df:1089:fa5] | 80, 443, 8080 | 3 |
| [2606:4700:9ad4:5795:7bce:88fa:bece:915a] | 80, 443, 8080 | 3 |
| [2606:4700:54:46e4:b78b:c257:668f:3de6] | 80, 443, 8080 | 3 |
| [2606:4700:9ad4:60b3:7a1e:13df:1089:fa5] | 80, 443, 8080 | 3 |
| [2606:4700:54:5e09:ff85:10e5:831b:b8b6] | 80, 443, 8080 | 13 |
| [2606:4700:28:1ab5:a357:5853:4196:251d] | 80, 443, 8080 | 13 |
| [2606:4700:54:5e09:ff85:10e5:831b:b8b6] | 80, 443, 8080 | 13 |
| [2606:4700:28:1ab5:a357:5853:4196:251d] | 80, 443, 8080 | 13 |
| [2606:4700:54:5e09:ff85:10e5:831b:b8b6] | 80, 443, 8080 | 13 |
| [2606:4700:28:1ab5:a357:5853:4196:251d] | 80, 443, 8080 | 13 |

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
