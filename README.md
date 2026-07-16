# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-17 01:01:39 +0330

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
| 198.41.208.163 | 80, 443, 8080 | 53 |
| 198.41.208.163 | 80, 443, 8080 | 53 |
| 198.41.208.108 | 80, 443, 8080 | 56 |
| 198.41.208.108 | 80, 443, 8080 | 56 |
| 104.16.106.250 | 80, 443, 8080 | 138 |
| 104.17.185.234 | 80, 443, 8080 | 139 |
| 104.18.209.144 | 80, 443, 8080 | 139 |
| 104.16.22.195 | 80, 443, 8080 | 139 |
| 104.19.162.71 | 80, 443, 8080 | 139 |
| 141.101.113.83 | 80, 443, 8080 | 185 |
| 141.101.113.83 | 80, 443, 8080 | 185 |
| 162.159.160.217 | 80, 443, 8080 | 195 |
| 162.159.160.217 | 80, 443, 8080 | 195 |
| 172.67.115.37 | 80, 443, 8080 | 203 |
| 172.67.115.37 | 80, 443, 8080 | 203 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90d4:f329:8433:75a1:7bd:ebf1] | 80, 443, 8080 | 0 |
| [2606:4700:83bc:a8c:b78e:9f10:fddb:a9ba] | 80, 443, 8080 | 0 |
| [2606:4700:90d4:f329:8433:75a1:7bd:ebf1] | 80, 443, 8080 | 0 |
| [2606:4700:83bc:a8c:b78e:9f10:fddb:a9ba] | 80, 443, 8080 | 0 |
| [2606:4700:90d4:f329:8433:75a1:7bd:ebf1] | 80, 443, 8080 | 0 |
| [2606:4700:83bc:a8c:b78e:9f10:fddb:a9ba] | 80, 443, 8080 | 0 |
| [2606:4700:3025:6fb6:34ff:eeab:745a:b1da] | 80, 443, 8080 | 1 |
| [2606:4700:136:6210:777e:6c3:8bce:b020] | 80, 443, 8080 | 1 |
| [2606:4700:976b:4732:e76b:b6b9:1625:3f08] | 80, 443, 8080 | 1 |
| [2606:4700:3025:6fb6:34ff:eeab:745a:b1da] | 80, 443, 8080 | 1 |
| [2606:4700:136:6210:777e:6c3:8bce:b020] | 80, 443, 8080 | 1 |
| [2606:4700:976b:4732:e76b:b6b9:1625:3f08] | 80, 443, 8080 | 1 |
| [2606:4700:3025:6fb6:34ff:eeab:745a:b1da] | 80, 443, 8080 | 1 |
| [2606:4700:136:6210:777e:6c3:8bce:b020] | 80, 443, 8080 | 1 |
| [2606:4700:976b:4732:e76b:b6b9:1625:3f08] | 80, 443, 8080 | 1 |

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
