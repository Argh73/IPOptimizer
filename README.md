# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-06 17:59:32 +0330

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
| 198.41.209.180 | 80, 443, 8080 | 63 |
| 198.41.209.180 | 80, 443, 8080 | 63 |
| 198.41.209.99 | 80, 443, 8080 | 75 |
| 198.41.211.115 | 80, 443, 8080 | 75 |
| 198.41.209.99 | 80, 443, 8080 | 75 |
| 198.41.209.229 | 80, 443, 8080 | 91 |
| 198.41.209.229 | 80, 443, 8080 | 91 |
| 198.41.209.220 | 80, 443, 8080 | 94 |
| 198.41.209.220 | 80, 443, 8080 | 94 |
| 172.67.154.244 | 80, 443, 8080 | 134 |
| 172.67.154.244 | 80, 443, 8080 | 134 |
| 104.19.107.230 | 80, 443, 8080 | 142 |
| 104.19.63.59 | 80, 443, 8080 | 142 |
| 104.19.145.21 | 80, 443, 8080 | 142 |
| 104.19.251.49 | 80, 443, 8080 | 142 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:5c:4d0e:ccf6:dfd8:58af:13ee] | 80, 443, 8080 | 3 |
| [2606:4700:5c:4d0e:ccf6:dfd8:58af:13ee] | 80, 443, 8080 | 3 |
| [2606:4700:5c:4d0e:ccf6:dfd8:58af:13ee] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:3335:50ac:418b:6758:635d] | 80, 443, 8080 | 4 |
| [2606:4700:8d9d:3335:50ac:418b:6758:635d] | 80, 443, 8080 | 4 |
| [2606:4700:8d9d:3335:50ac:418b:6758:635d] | 80, 443, 8080 | 4 |
| [2606:4700:e:86cd:bc57:b8cd:2039:f78c] | 80, 443, 8080 | 13 |
| [2606:4700:5c:2ff7:dd64:d3a8:5c25:e5f9] | 80, 443, 8080 | 13 |
| [2606:4700:e:86cd:bc57:b8cd:2039:f78c] | 80, 443, 8080 | 13 |
| [2606:4700:5c:2ff7:dd64:d3a8:5c25:e5f9] | 80, 443, 8080 | 13 |
| [2606:4700:e:86cd:bc57:b8cd:2039:f78c] | 80, 443, 8080 | 13 |
| [2606:4700:5c:2ff7:dd64:d3a8:5c25:e5f9] | 80, 443, 8080 | 13 |
| [2606:4700:90c0:5861:1c16:4636:9897:76ba] | 80, 443, 8080 | 163 |
| [2606:4700:90c0:5861:1c16:4636:9897:76ba] | 80, 443, 8080 | 163 |
| [2606:4700:90c0:5861:1c16:4636:9897:76ba] | 80, 443, 8080 | 163 |

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
