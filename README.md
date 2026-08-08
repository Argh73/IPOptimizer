# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-09 00:28:32 +0330

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
| 198.41.208.119 | 80, 443, 8080 | 51 |
| 198.41.208.119 | 80, 443, 8080 | 51 |
| 198.41.209.35 | 80, 443, 8080 | 53 |
| 198.41.209.35 | 80, 443, 8080 | 53 |
| 198.41.208.18 | 80, 443, 8080 | 60 |
| 198.41.208.18 | 80, 443, 8080 | 60 |
| 104.19.3.54 | 80, 443, 8080 | 138 |
| 104.19.249.171 | 80, 443, 8080 | 138 |
| 104.18.17.166 | 80, 443, 8080 | 139 |
| 104.18.126.217 | 80, 443, 8080 | 139 |
| 104.19.64.204 | 80, 443, 8080 | 139 |
| 198.41.208.35 | 80, 443, 8080 | 154 |
| 198.41.208.35 | 80, 443, 8080 | 154 |
| 162.159.160.215 | 80, 443, 8080 | 186 |
| 162.159.160.215 | 80, 443, 8080 | 186 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3035:3f8a:c366:2621:2a53:29e6] | 80, 443, 8080 | 0 |
| [2606:4700:3035:3f8a:c366:2621:2a53:29e6] | 80, 443, 8080 | 0 |
| [2606:4700:3035:3f8a:c366:2621:2a53:29e6] | 80, 443, 8080 | 0 |
| [2606:4700:83bf:e161:912e:449:ed77:769e] | 80, 443, 8080 | 1 |
| [2606:4700:90df:e856:f2d0:1645:c4c4:148d] | 80, 443, 8080 | 1 |
| [2606:4700:83bf:e161:912e:449:ed77:769e] | 80, 443, 8080 | 1 |
| [2606:4700:90df:e856:f2d0:1645:c4c4:148d] | 80, 443, 8080 | 1 |
| [2606:4700:83bf:e161:912e:449:ed77:769e] | 80, 443, 8080 | 1 |
| [2606:4700:90df:e856:f2d0:1645:c4c4:148d] | 80, 443, 8080 | 1 |
| [2606:4700:8ca9:c92b:9682:bb58:d4bf:dda6] | 80, 443, 8080 | 136 |
| [2606:4700:8ca9:9bb8:3736:b7e4:509b:ba23] | 80, 443, 8080 | 136 |
| [2606:4700:8ca9:c92b:9682:bb58:d4bf:dda6] | 80, 443, 8080 | 136 |
| [2606:4700:8ca9:9bb8:3736:b7e4:509b:ba23] | 80, 443, 8080 | 136 |
| [2606:4700:8ca9:c92b:9682:bb58:d4bf:dda6] | 80, 443, 8080 | 136 |
| [2606:4700:8ca9:9bb8:3736:b7e4:509b:ba23] | 80, 443, 8080 | 136 |

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
