# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-16 02:31:42 +0330

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
| 198.41.208.73 | 80, 443, 8080 | 48 |
| 198.41.209.139 | 80, 443, 8080 | 48 |
| 198.41.209.184 | 80, 443, 8080 | 48 |
| 198.41.208.237 | 80, 443, 8080 | 48 |
| 198.41.208.73 | 80, 443, 8080 | 48 |
| 198.41.209.139 | 80, 443, 8080 | 48 |
| 198.41.209.184 | 80, 443, 8080 | 48 |
| 198.41.208.237 | 80, 443, 8080 | 48 |
| 198.41.208.188 | 80, 443, 8080 | 50 |
| 198.41.208.188 | 80, 443, 8080 | 50 |
| 104.18.202.72 | 80, 443, 8080 | 138 |
| 104.16.212.50 | 80, 443, 8080 | 138 |
| 104.19.212.194 | 80, 443, 8080 | 138 |
| 104.16.87.187 | 80, 443, 8080 | 138 |
| 104.16.83.36 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b0b:3118:2a18:f18d:927b:8ae2] | 80, 443, 8080 | 3 |
| [2606:4700:9b0b:303a:3665:77c9:5682:36f3] | 80, 443, 8080 | 3 |
| [2606:4700:9a6d:4875:c228:1628:c1a7:ba04] | 80, 443, 8080 | 3 |
| [2606:4700:90cd:194a:4514:bc17:b793:8e27] | 80, 443, 8080 | 3 |
| [2606:4700:90cd:8b57:1db1:3c26:e1f:471f] | 80, 443, 8080 | 3 |
| [2606:4700:9b0b:3118:2a18:f18d:927b:8ae2] | 80, 443, 8080 | 3 |
| [2606:4700:9b0b:303a:3665:77c9:5682:36f3] | 80, 443, 8080 | 3 |
| [2606:4700:9a6d:4875:c228:1628:c1a7:ba04] | 80, 443, 8080 | 3 |
| [2606:4700:90cd:194a:4514:bc17:b793:8e27] | 80, 443, 8080 | 3 |
| [2606:4700:90cd:8b57:1db1:3c26:e1f:471f] | 80, 443, 8080 | 3 |
| [2606:4700:9b0b:3118:2a18:f18d:927b:8ae2] | 80, 443, 8080 | 3 |
| [2606:4700:9b0b:303a:3665:77c9:5682:36f3] | 80, 443, 8080 | 3 |
| [2606:4700:9a6d:4875:c228:1628:c1a7:ba04] | 80, 443, 8080 | 3 |
| [2606:4700:90cd:194a:4514:bc17:b793:8e27] | 80, 443, 8080 | 3 |
| [2606:4700:90cd:8b57:1db1:3c26:e1f:471f] | 80, 443, 8080 | 3 |

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
