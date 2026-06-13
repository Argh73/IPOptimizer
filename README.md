# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-14 01:14:23 +0330

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
| 198.41.209.110 | 80, 443, 8080 | 51 |
| 198.41.208.186 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.110 | 80, 443, 8080 | 51 |
| 198.41.208.186 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.10 | 80, 443, 8080 | 52 |
| 198.41.209.132 | 80, 443, 8080 | 52 |
| 198.41.209.10 | 80, 443, 8080 | 52 |
| 198.41.209.132 | 80, 443, 8080 | 52 |
| 104.18.70.111 | 80, 443, 8080 | 129 |
| 104.17.20.191 | 80, 443, 8080 | 130 |
| 104.19.112.101 | 80, 443, 8080 | 130 |
| 104.18.178.252 | 80, 443, 8080 | 130 |
| 104.17.251.104 | 80, 443, 8080 | 130 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:964c:70d9:3941:90d:2f50:933] | 80, 443, 8080 | 1 |
| [2606:4700:15:cc69:49a3:e536:1c72:944b] | 80, 443, 8080 | 1 |
| [2606:4700:964c:70d9:3941:90d:2f50:933] | 80, 443, 8080 | 1 |
| [2606:4700:15:cc69:49a3:e536:1c72:944b] | 80, 443, 8080 | 1 |
| [2606:4700:964c:70d9:3941:90d:2f50:933] | 80, 443, 8080 | 1 |
| [2606:4700:15:cc69:49a3:e536:1c72:944b] | 80, 443, 8080 | 1 |
| [2606:4700:2d:2a31:b218:73d2:41b:3a1e] | 80, 443, 8080 | 3 |
| [2606:4700:3014:9aab:3047:6584:9a84:512b] | 80, 443, 8080 | 3 |
| [2606:4700:2d:2a31:b218:73d2:41b:3a1e] | 80, 443, 8080 | 3 |
| [2606:4700:3014:9aab:3047:6584:9a84:512b] | 80, 443, 8080 | 3 |
| [2606:4700:2d:2a31:b218:73d2:41b:3a1e] | 80, 443, 8080 | 3 |
| [2606:4700:3014:9aab:3047:6584:9a84:512b] | 80, 443, 8080 | 3 |
| [2606:4700:4400:9efa:c8e3:a18d:a6a5:a8d0] | 80, 443, 8080 | 12 |
| [2606:4700:4400:9efa:c8e3:a18d:a6a5:a8d0] | 80, 443, 8080 | 12 |
| [2606:4700:4400:9efa:c8e3:a18d:a6a5:a8d0] | 80, 443, 8080 | 12 |

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
