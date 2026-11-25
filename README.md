# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-25 21:00:15 +0330

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
| 104.19.61.76 | 80, 443, 8080 | 140 |
| 162.159.241.222 | 80, 443, 8080 | 140 |
| 104.18.131.92 | 80, 443, 8080 | 142 |
| 104.18.117.3 | 80, 443, 8080 | 142 |
| 104.16.121.76 | 80, 443, 8080 | 143 |
| 162.159.160.197 | 80, 443, 8080 | 150 |
| 162.159.160.197 | 80, 443, 8080 | 150 |
| 162.159.153.9 | 80, 443, 8080 | 166 |
| 162.159.153.9 | 80, 443, 8080 | 166 |
| 162.159.152.249 | 80, 443, 8080 | 168 |
| 162.159.152.249 | 80, 443, 8080 | 168 |
| 162.159.136.220 | 80, 443, 8080 | 169 |
| 162.159.130.228 | 80, 443, 8080 | 169 |
| 162.159.136.220 | 80, 443, 8080 | 169 |
| 162.159.130.228 | 80, 443, 8080 | 169 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8deb:bfca:cede:76da:6f64:c9e0] | 80, 443, 8080 | 3 |
| [2606:4700:8397:9f6b:219a:e3db:98f9:811] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:9dd0:3da7:885d:557:de78] | 80, 443, 8080 | 3 |
| [2606:4700:130:b52b:2d83:973c:4faf:1f0d] | 80, 443, 8080 | 3 |
| [2606:4700:9add:d138:9256:4d9:1fe:1f8c] | 80, 443, 8080 | 3 |
| [2606:4700:8deb:bfca:cede:76da:6f64:c9e0] | 80, 443, 8080 | 3 |
| [2606:4700:8397:9f6b:219a:e3db:98f9:811] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:9dd0:3da7:885d:557:de78] | 80, 443, 8080 | 3 |
| [2606:4700:130:b52b:2d83:973c:4faf:1f0d] | 80, 443, 8080 | 3 |
| [2606:4700:9add:d138:9256:4d9:1fe:1f8c] | 80, 443, 8080 | 3 |
| [2606:4700:8deb:bfca:cede:76da:6f64:c9e0] | 80, 443, 8080 | 3 |
| [2606:4700:8397:9f6b:219a:e3db:98f9:811] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:9dd0:3da7:885d:557:de78] | 80, 443, 8080 | 3 |
| [2606:4700:130:b52b:2d83:973c:4faf:1f0d] | 80, 443, 8080 | 3 |
| [2606:4700:9add:d138:9256:4d9:1fe:1f8c] | 80, 443, 8080 | 3 |

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
