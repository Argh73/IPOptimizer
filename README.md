# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-11 15:11:09 +0330

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
| 198.41.208.197 | 80, 443, 8080 | 47 |
| 198.41.208.197 | 80, 443, 8080 | 47 |
| 198.41.209.151 | 80, 443, 8080 | 48 |
| 198.41.209.151 | 80, 443, 8080 | 48 |
| 198.41.208.170 | 80, 443, 8080 | 50 |
| 198.41.208.170 | 80, 443, 8080 | 50 |
| 198.41.208.17 | 80, 443, 8080 | 58 |
| 198.41.208.17 | 80, 443, 8080 | 58 |
| 198.41.209.45 | 80, 443, 8080 | 83 |
| 198.41.209.45 | 80, 443, 8080 | 83 |
| 104.18.164.218 | 80, 443, 8080 | 157 |
| 104.18.193.191 | 80, 443, 8080 | 159 |
| 104.16.185.131 | 80, 443, 8080 | 160 |
| 104.17.138.64 | 80, 443, 8080 | 165 |
| 104.18.238.216 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8399:25d3:62b8:4914:3864:e7df] | 80, 443, 8080 | 3 |
| [2606:4700:9ae5:129c:9d9e:10de:b8ad:a5dc] | 80, 443, 8080 | 3 |
| [2606:4700:9ae5:e5d3:6531:4094:62cf:b652] | 80, 443, 8080 | 3 |
| [2606:4700:8399:e12c:cd24:dc23:600e:3639] | 80, 443, 8080 | 3 |
| [2606:4700:8399:25d3:62b8:4914:3864:e7df] | 80, 443, 8080 | 3 |
| [2606:4700:9ae5:129c:9d9e:10de:b8ad:a5dc] | 80, 443, 8080 | 3 |
| [2606:4700:9ae5:e5d3:6531:4094:62cf:b652] | 80, 443, 8080 | 3 |
| [2606:4700:8399:e12c:cd24:dc23:600e:3639] | 80, 443, 8080 | 3 |
| [2606:4700:8399:25d3:62b8:4914:3864:e7df] | 80, 443, 8080 | 3 |
| [2606:4700:9ae5:129c:9d9e:10de:b8ad:a5dc] | 80, 443, 8080 | 3 |
| [2606:4700:9ae5:e5d3:6531:4094:62cf:b652] | 80, 443, 8080 | 3 |
| [2606:4700:8399:e12c:cd24:dc23:600e:3639] | 80, 443, 8080 | 3 |
| [2606:4700:83b8:8435:e7e2:8570:5aba:efa5] | 80, 443, 8080 | 157 |
| [2606:4700:83b8:8435:e7e2:8570:5aba:efa5] | 80, 443, 8080 | 157 |
| [2606:4700:83b8:8435:e7e2:8570:5aba:efa5] | 80, 443, 8080 | 157 |

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
