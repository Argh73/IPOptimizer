# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-03 03:26:19 +0330

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
| 198.41.208.51 | 80, 443, 8080 | 51 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.209.200 | 80, 443, 8080 | 66 |
| 198.41.211.3 | 80, 443, 8080 | 76 |
| 172.67.156.215 | 80, 443, 8080 | 130 |
| 172.67.166.217 | 80, 443, 8080 | 133 |
| 172.67.160.57 | 80, 443, 8080 | 135 |
| 104.18.120.124 | 80, 443, 8080 | 139 |
| 104.16.191.213 | 80, 443, 8080 | 139 |
| 104.17.78.182 | 80, 443, 8080 | 140 |
| 104.17.129.70 | 80, 443, 8080 | 140 |
| 172.67.251.117 | 80, 443, 8080 | 145 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91b0:8ec2:373d:197f:627d:49df] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:5b47:d20b:af96:9c47:ec63] | 80, 443, 8080 | 3 |
| [2606:4700:976a:21f5:e3ed:fbaf:1371:ef45] | 80, 443, 8080 | 3 |
| [2606:4700:976a:83e5:848a:2fd9:10f3:47ac] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:8ec2:373d:197f:627d:49df] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:5b47:d20b:af96:9c47:ec63] | 80, 443, 8080 | 3 |
| [2606:4700:976a:21f5:e3ed:fbaf:1371:ef45] | 80, 443, 8080 | 3 |
| [2606:4700:976a:83e5:848a:2fd9:10f3:47ac] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:8ec2:373d:197f:627d:49df] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:5b47:d20b:af96:9c47:ec63] | 80, 443, 8080 | 3 |
| [2606:4700:976a:21f5:e3ed:fbaf:1371:ef45] | 80, 443, 8080 | 3 |
| [2606:4700:976a:83e5:848a:2fd9:10f3:47ac] | 80, 443, 8080 | 3 |
| [2606:4700:0:15b2:f3a5:1732:7c5:6680] | 80, 443, 8080 | 13 |
| [2606:4700:0:15b2:f3a5:1732:7c5:6680] | 80, 443, 8080 | 13 |
| [2606:4700:0:15b2:f3a5:1732:7c5:6680] | 80, 443, 8080 | 13 |

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
