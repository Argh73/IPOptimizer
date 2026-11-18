# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-18 19:23:59 +0330

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
| 162.159.134.219 | 80, 443, 8080 | 95 |
| 162.159.134.219 | 80, 443, 8080 | 95 |
| 162.159.152.48 | 80, 443, 8080 | 98 |
| 162.159.152.48 | 80, 443, 8080 | 98 |
| 104.16.2.187 | 80, 443, 8080 | 141 |
| 104.19.51.26 | 80, 443, 8080 | 142 |
| 104.19.39.8 | 80, 443, 8080 | 142 |
| 162.159.240.147 | 80, 443, 8080 | 142 |
| 104.19.11.253 | 80, 443, 8080 | 143 |
| 162.159.160.5 | 80, 443, 8080 | 152 |
| 162.159.160.5 | 80, 443, 8080 | 152 |
| 162.159.160.96 | 80, 443, 8080 | 159 |
| 162.159.160.96 | 80, 443, 8080 | 159 |
| 162.159.160.196 | 80, 443, 8080 | 162 |
| 162.159.160.196 | 80, 443, 8080 | 162 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de7:e32:a6ea:933f:2c6c:dce6] | 80, 443, 8080 | 3 |
| [2606:4700:8393:e009:fdef:1455:48a8:7489] | 80, 443, 8080 | 3 |
| [2606:4700:8393:1e8f:5587:8212:79d3:2d29] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:4151:95b0:ed0b:7f16:d710] | 80, 443, 8080 | 3 |
| [2606:4700:8de5:5b09:7931:364d:2f8f:29e1] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:e32:a6ea:933f:2c6c:dce6] | 80, 443, 8080 | 3 |
| [2606:4700:8393:e009:fdef:1455:48a8:7489] | 80, 443, 8080 | 3 |
| [2606:4700:8393:1e8f:5587:8212:79d3:2d29] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:4151:95b0:ed0b:7f16:d710] | 80, 443, 8080 | 3 |
| [2606:4700:8de5:5b09:7931:364d:2f8f:29e1] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:e32:a6ea:933f:2c6c:dce6] | 80, 443, 8080 | 3 |
| [2606:4700:8393:e009:fdef:1455:48a8:7489] | 80, 443, 8080 | 3 |
| [2606:4700:8393:1e8f:5587:8212:79d3:2d29] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:4151:95b0:ed0b:7f16:d710] | 80, 443, 8080 | 3 |
| [2606:4700:8de5:5b09:7931:364d:2f8f:29e1] | 80, 443, 8080 | 3 |

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
