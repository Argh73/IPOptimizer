# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-27 01:17:15 +0330

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
| 198.41.208.174 | 80, 443, 8080 | 41 |
| 198.41.208.174 | 80, 443, 8080 | 41 |
| 198.41.208.55 | 80, 443, 8080 | 51 |
| 198.41.208.103 | 80, 443, 8080 | 51 |
| 198.41.208.197 | 80, 443, 8080 | 51 |
| 198.41.209.214 | 80, 443, 8080 | 51 |
| 198.41.208.55 | 80, 443, 8080 | 51 |
| 198.41.208.103 | 80, 443, 8080 | 51 |
| 198.41.208.197 | 80, 443, 8080 | 51 |
| 198.41.209.214 | 80, 443, 8080 | 51 |
| 198.41.222.199 | 80, 443, 8080 | 71 |
| 104.19.116.52 | 80, 443, 8080 | 130 |
| 104.17.249.128 | 80, 443, 8080 | 130 |
| 104.16.78.119 | 80, 443, 8080 | 130 |
| 104.21.229.205 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3:65ed:30d4:e944:3e3:18d9] | 80, 443, 8080 | 3 |
| [2606:4700:839b:21e1:a750:4ee7:e8b3:dc7c] | 80, 443, 8080 | 3 |
| [2606:4700:839b:ea31:4e51:cadf:1151:7c09] | 80, 443, 8080 | 3 |
| [2606:4700:3:65ed:30d4:e944:3e3:18d9] | 80, 443, 8080 | 3 |
| [2606:4700:839b:21e1:a750:4ee7:e8b3:dc7c] | 80, 443, 8080 | 3 |
| [2606:4700:839b:ea31:4e51:cadf:1151:7c09] | 80, 443, 8080 | 3 |
| [2606:4700:3:65ed:30d4:e944:3e3:18d9] | 80, 443, 8080 | 3 |
| [2606:4700:839b:21e1:a750:4ee7:e8b3:dc7c] | 80, 443, 8080 | 3 |
| [2606:4700:839b:ea31:4e51:cadf:1151:7c09] | 80, 443, 8080 | 3 |
| [2606:4700:8d73:f97a:f255:5a06:b99b:2375] | 80, 443, 8080 | 4 |
| [2606:4700:8d73:f97a:f255:5a06:b99b:2375] | 80, 443, 8080 | 4 |
| [2606:4700:8d73:f97a:f255:5a06:b99b:2375] | 80, 443, 8080 | 4 |
| [2606:4700:3:18c4:3ad3:5457:950:6313] | 80, 443, 8080 | 13 |
| [2606:4700:3:18c4:3ad3:5457:950:6313] | 80, 443, 8080 | 13 |
| [2606:4700:3:18c4:3ad3:5457:950:6313] | 80, 443, 8080 | 13 |

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
