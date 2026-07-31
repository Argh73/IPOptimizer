# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-01 01:07:06 +0330

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
| 198.41.209.214 | 80, 443, 8080 | 51 |
| 198.41.209.214 | 80, 443, 8080 | 51 |
| 198.41.208.63 | 80, 443, 8080 | 53 |
| 198.41.208.63 | 80, 443, 8080 | 53 |
| 198.41.208.163 | 80, 443, 8080 | 56 |
| 198.41.208.163 | 80, 443, 8080 | 56 |
| 198.41.208.104 | 80, 443, 8080 | 73 |
| 198.41.208.104 | 80, 443, 8080 | 73 |
| 198.41.208.165 | 80, 443, 8080 | 95 |
| 198.41.208.165 | 80, 443, 8080 | 95 |
| 104.16.155.252 | 80, 443, 8080 | 138 |
| 104.16.66.237 | 80, 443, 8080 | 138 |
| 104.19.207.99 | 80, 443, 8080 | 139 |
| 104.18.120.84 | 80, 443, 8080 | 140 |
| 172.64.91.66 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de2:dbe5:53be:8afc:efc1:aac0] | 80, 443, 8080 | 1 |
| [2606:4700:2c:2284:d4f1:2a47:cea2:a46f] | 80, 443, 8080 | 1 |
| [2606:4700:8dd7:6068:58de:f012:4cba:e8b2] | 80, 443, 8080 | 1 |
| [2606:4700:8de2:dbe5:53be:8afc:efc1:aac0] | 80, 443, 8080 | 1 |
| [2606:4700:2c:2284:d4f1:2a47:cea2:a46f] | 80, 443, 8080 | 1 |
| [2606:4700:8dd7:6068:58de:f012:4cba:e8b2] | 80, 443, 8080 | 1 |
| [2606:4700:8de2:dbe5:53be:8afc:efc1:aac0] | 80, 443, 8080 | 1 |
| [2606:4700:2c:2284:d4f1:2a47:cea2:a46f] | 80, 443, 8080 | 1 |
| [2606:4700:8dd7:6068:58de:f012:4cba:e8b2] | 80, 443, 8080 | 1 |
| [2606:4700:8ca8:a974:e72c:a6cc:3778:f808] | 80, 443, 8080 | 131 |
| [2606:4700:8ca8:a974:e72c:a6cc:3778:f808] | 80, 443, 8080 | 131 |
| [2606:4700:8ca8:a974:e72c:a6cc:3778:f808] | 80, 443, 8080 | 131 |
| [2606:4700:8ca8:acb4:158f:8396:5628:cc87] | 80, 443, 8080 | 141 |
| [2606:4700:8ca8:acb4:158f:8396:5628:cc87] | 80, 443, 8080 | 141 |
| [2606:4700:8ca8:acb4:158f:8396:5628:cc87] | 80, 443, 8080 | 141 |

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
