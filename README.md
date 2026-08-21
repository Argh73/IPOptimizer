# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-22 00:19:09 +0330

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
| 104.17.126.32 | 80, 443, 8080 | 131 |
| 104.17.126.32 | 80, 443, 8080 | 131 |
| 104.17.126.32 | 80, 443, 8080 | 131 |
| 104.17.76.98 | 80, 443, 8080 | 140 |
| 104.17.76.98 | 80, 443, 8080 | 140 |
| 104.17.76.98 | 80, 443, 8080 | 140 |
| 104.18.3.54 | 80, 443, 8080 | 141 |
| 104.17.81.51 | 80, 443, 8080 | 141 |
| 104.18.3.54 | 80, 443, 8080 | 141 |
| 104.17.81.51 | 80, 443, 8080 | 141 |
| 104.18.3.54 | 80, 443, 8080 | 141 |
| 104.17.81.51 | 80, 443, 8080 | 141 |
| 104.16.83.94 | 80, 443, 8080 | 147 |
| 104.16.83.94 | 80, 443, 8080 | 147 |
| 104.16.83.94 | 80, 443, 8080 | 147 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90db:c928:8805:9346:544f:5e5b] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:9acd:c687:e0e3:6408:dbda] | 80, 443, 8080 | 3 |
| [2606:4700:3035:c292:7ae0:915a:5b76:7141] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:4405:cc9d:28f:a14f:d975] | 80, 443, 8080 | 3 |
| [2606:4700:90db:c928:8805:9346:544f:5e5b] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:9acd:c687:e0e3:6408:dbda] | 80, 443, 8080 | 3 |
| [2606:4700:3035:c292:7ae0:915a:5b76:7141] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:4405:cc9d:28f:a14f:d975] | 80, 443, 8080 | 3 |
| [2606:4700:90db:c928:8805:9346:544f:5e5b] | 80, 443, 8080 | 3 |
| [2606:4700:9c6b:9acd:c687:e0e3:6408:dbda] | 80, 443, 8080 | 3 |
| [2606:4700:3035:c292:7ae0:915a:5b76:7141] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:4405:cc9d:28f:a14f:d975] | 80, 443, 8080 | 3 |
| [2606:4700:3035:5983:bfb0:c97e:1108:534a] | 80, 443, 8080 | 13 |
| [2606:4700:3035:5983:bfb0:c97e:1108:534a] | 80, 443, 8080 | 13 |
| [2606:4700:3035:5983:bfb0:c97e:1108:534a] | 80, 443, 8080 | 13 |

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
