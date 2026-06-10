# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-10 14:11:18 +0330

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
| 198.41.208.236 | 80, 443, 8080 | 55 |
| 198.41.208.236 | 80, 443, 8080 | 55 |
| 198.41.209.243 | 80, 443, 8080 | 56 |
| 198.41.209.243 | 80, 443, 8080 | 56 |
| 198.41.208.220 | 80, 443, 8080 | 57 |
| 198.41.208.220 | 80, 443, 8080 | 57 |
| 162.159.36.152 | 80, 443, 8080 | 64 |
| 162.159.36.113 | 80, 443, 8080 | 74 |
| 198.41.222.103 | 80, 443, 8080 | 78 |
| 162.159.36.79 | 80, 443, 8080 | 86 |
| 162.159.36.173 | 80, 443, 8080 | 90 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3056:524b:ae83:b1ad:dc9e:4216] | 80, 443, 8080 | 0 |
| [2606:4700:3056:969f:538c:f2c4:2eac:b7b5] | 80, 443, 8080 | 0 |
| [2606:4700:3056:524b:ae83:b1ad:dc9e:4216] | 80, 443, 8080 | 0 |
| [2606:4700:3056:969f:538c:f2c4:2eac:b7b5] | 80, 443, 8080 | 0 |
| [2606:4700:3056:524b:ae83:b1ad:dc9e:4216] | 80, 443, 8080 | 0 |
| [2606:4700:3056:969f:538c:f2c4:2eac:b7b5] | 80, 443, 8080 | 0 |
| [2606:4700:8def:a9b3:1b6f:ed8a:fa84:c3bb] | 80, 443, 8080 | 1 |
| [2606:4700:8def:a9b3:1b6f:ed8a:fa84:c3bb] | 80, 443, 8080 | 1 |
| [2606:4700:8def:a9b3:1b6f:ed8a:fa84:c3bb] | 80, 443, 8080 | 1 |
| [2606:4700:9c6c:9308:e78d:9a03:c76b:c533] | 80, 443, 8080 | 3 |
| [2606:4700:9c6c:13d3:c515:54bd:1b80:1614] | 80, 443, 8080 | 3 |
| [2606:4700:9c6c:9308:e78d:9a03:c76b:c533] | 80, 443, 8080 | 3 |
| [2606:4700:9c6c:13d3:c515:54bd:1b80:1614] | 80, 443, 8080 | 3 |
| [2606:4700:9c6c:9308:e78d:9a03:c76b:c533] | 80, 443, 8080 | 3 |
| [2606:4700:9c6c:13d3:c515:54bd:1b80:1614] | 80, 443, 8080 | 3 |

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
