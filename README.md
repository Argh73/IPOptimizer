# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-24 01:25:59 +0330

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
| 198.41.209.170 | 80, 443, 8080 | 52 |
| 198.41.208.55 | 80, 443, 8080 | 52 |
| 198.41.208.112 | 80, 443, 8080 | 52 |
| 198.41.209.170 | 80, 443, 8080 | 52 |
| 198.41.208.55 | 80, 443, 8080 | 52 |
| 198.41.208.112 | 80, 443, 8080 | 52 |
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.209.162 | 80, 443, 8080 | 53 |
| 198.41.208.201 | 80, 443, 8080 | 54 |
| 198.41.208.201 | 80, 443, 8080 | 54 |
| 104.17.41.43 | 80, 443, 8080 | 130 |
| 104.17.166.23 | 80, 443, 8080 | 132 |
| 104.19.250.63 | 80, 443, 8080 | 140 |
| 172.64.93.87 | 80, 443, 8080 | 141 |
| 104.16.220.48 | 80, 443, 8080 | 145 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ae6:d83b:7d3:dfe6:9e0a:6f52] | 80, 443, 8080 | 0 |
| [2606:4700:90ca:aa31:88f8:f399:3130:353a] | 80, 443, 8080 | 0 |
| [2606:4700:839f:10d6:66fe:3a2a:a466:5666] | 80, 443, 8080 | 0 |
| [2606:4700:9ae6:d83b:7d3:dfe6:9e0a:6f52] | 80, 443, 8080 | 0 |
| [2606:4700:90ca:aa31:88f8:f399:3130:353a] | 80, 443, 8080 | 0 |
| [2606:4700:839f:10d6:66fe:3a2a:a466:5666] | 80, 443, 8080 | 0 |
| [2606:4700:9ae6:d83b:7d3:dfe6:9e0a:6f52] | 80, 443, 8080 | 0 |
| [2606:4700:90ca:aa31:88f8:f399:3130:353a] | 80, 443, 8080 | 0 |
| [2606:4700:839f:10d6:66fe:3a2a:a466:5666] | 80, 443, 8080 | 0 |
| [2606:4700:9ae6:bc5d:efdd:e6dc:1b9e:adcd] | 80, 443, 8080 | 1 |
| [2606:4700:90ca:d948:223b:dc17:2a7d:c783] | 80, 443, 8080 | 1 |
| [2606:4700:9ae6:bc5d:efdd:e6dc:1b9e:adcd] | 80, 443, 8080 | 1 |
| [2606:4700:90ca:d948:223b:dc17:2a7d:c783] | 80, 443, 8080 | 1 |
| [2606:4700:9ae6:bc5d:efdd:e6dc:1b9e:adcd] | 80, 443, 8080 | 1 |
| [2606:4700:90ca:d948:223b:dc17:2a7d:c783] | 80, 443, 8080 | 1 |

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
