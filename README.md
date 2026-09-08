# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-08 15:05:58 +0330

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
| 198.41.208.40 | 80, 443, 8080 | 47 |
| 198.41.208.40 | 80, 443, 8080 | 47 |
| 198.41.208.213 | 80, 443, 8080 | 48 |
| 198.41.208.213 | 80, 443, 8080 | 48 |
| 198.41.209.233 | 80, 443, 8080 | 50 |
| 198.41.209.233 | 80, 443, 8080 | 50 |
| 198.41.208.220 | 80, 443, 8080 | 59 |
| 198.41.208.220 | 80, 443, 8080 | 59 |
| 198.41.209.14 | 80, 443, 8080 | 60 |
| 198.41.209.14 | 80, 443, 8080 | 60 |
| 104.19.239.206 | 80, 443, 8080 | 139 |
| 104.16.7.78 | 80, 443, 8080 | 139 |
| 104.19.243.102 | 80, 443, 8080 | 140 |
| 104.17.8.113 | 80, 443, 8080 | 141 |
| 104.18.253.196 | 80, 443, 8080 | 151 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:b:4ece:6096:a0e0:30b3:d36e] | 80, 443, 8080 | 3 |
| [2606:4700:b:4ece:6096:a0e0:30b3:d36e] | 80, 443, 8080 | 3 |
| [2606:4700:b:4ece:6096:a0e0:30b3:d36e] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:1d2c:458d:75dd:f54:932] | 80, 443, 8080 | 4 |
| [2606:4700:9b05:1d2c:458d:75dd:f54:932] | 80, 443, 8080 | 4 |
| [2606:4700:9b05:1d2c:458d:75dd:f54:932] | 80, 443, 8080 | 4 |
| [2606:4700:9ae3:217c:9515:6e94:98bc:f534] | 80, 443, 8080 | 5 |
| [2606:4700:9ae3:217c:9515:6e94:98bc:f534] | 80, 443, 8080 | 5 |
| [2606:4700:9ae3:217c:9515:6e94:98bc:f534] | 80, 443, 8080 | 5 |
| [2606:4700:440c:de26:2e6:452a:21ad:466d] | 80, 443, 8080 | 13 |
| [2606:4700:b:4ea0:ca7a:471d:866d:6e9d] | 80, 443, 8080 | 13 |
| [2606:4700:440c:de26:2e6:452a:21ad:466d] | 80, 443, 8080 | 13 |
| [2606:4700:b:4ea0:ca7a:471d:866d:6e9d] | 80, 443, 8080 | 13 |
| [2606:4700:440c:de26:2e6:452a:21ad:466d] | 80, 443, 8080 | 13 |
| [2606:4700:b:4ea0:ca7a:471d:866d:6e9d] | 80, 443, 8080 | 13 |

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
