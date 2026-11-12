# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-12 05:27:34 +0330

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
| 198.41.208.188 | 80, 443, 8080 | 52 |
| 198.41.208.188 | 80, 443, 8080 | 52 |
| 198.41.209.124 | 80, 443, 8080 | 59 |
| 198.41.209.124 | 80, 443, 8080 | 59 |
| 198.41.209.108 | 80, 443, 8080 | 63 |
| 198.41.209.108 | 80, 443, 8080 | 63 |
| 162.159.46.235 | 80, 443, 8080 | 82 |
| 198.41.208.144 | 80, 443, 8080 | 90 |
| 198.41.208.144 | 80, 443, 8080 | 90 |
| 198.41.208.113 | 80, 443, 8080 | 124 |
| 198.41.208.113 | 80, 443, 8080 | 124 |
| 104.19.130.15 | 80, 443, 8080 | 139 |
| 104.18.86.129 | 80, 443, 8080 | 142 |
| 104.19.109.109 | 80, 443, 8080 | 150 |
| 104.24.18.15 | 80, 443, 8080 | 164 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dd6:4305:2b3a:fb74:c817:44dd] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:6e96:5a62:ea90:2b27:805c] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:a9b7:88e6:1964:479:6ff7] | 80, 443, 8080 | 3 |
| [2606:4700:8d7b:67ca:2353:c6ad:34df:247] | 80, 443, 8080 | 3 |
| [2606:4700:8d7b:282b:3f2d:358:bbea:f998] | 80, 443, 8080 | 3 |
| [2606:4700:8dd6:4305:2b3a:fb74:c817:44dd] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:6e96:5a62:ea90:2b27:805c] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:a9b7:88e6:1964:479:6ff7] | 80, 443, 8080 | 3 |
| [2606:4700:8d7b:67ca:2353:c6ad:34df:247] | 80, 443, 8080 | 3 |
| [2606:4700:8d7b:282b:3f2d:358:bbea:f998] | 80, 443, 8080 | 3 |
| [2606:4700:8dd6:4305:2b3a:fb74:c817:44dd] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:6e96:5a62:ea90:2b27:805c] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:a9b7:88e6:1964:479:6ff7] | 80, 443, 8080 | 3 |
| [2606:4700:8d7b:67ca:2353:c6ad:34df:247] | 80, 443, 8080 | 3 |
| [2606:4700:8d7b:282b:3f2d:358:bbea:f998] | 80, 443, 8080 | 3 |

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
