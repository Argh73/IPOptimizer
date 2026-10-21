# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-21 15:41:49 +0330

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
| 198.41.208.75 | 80, 443, 8080 | 59 |
| 198.41.208.75 | 80, 443, 8080 | 59 |
| 198.41.209.137 | 80, 443, 8080 | 60 |
| 198.41.209.137 | 80, 443, 8080 | 60 |
| 172.67.151.188 | 80, 443, 8080 | 136 |
| 172.67.151.188 | 80, 443, 8080 | 136 |
| 172.67.64.171 | 80, 443, 8080 | 137 |
| 172.67.64.171 | 80, 443, 8080 | 137 |
| 104.16.146.29 | 80, 443, 8080 | 140 |
| 104.19.55.116 | 80, 443, 8080 | 141 |
| 104.16.10.185 | 80, 443, 8080 | 141 |
| 104.18.244.212 | 80, 443, 8080 | 141 |
| 104.16.10.178 | 80, 443, 8080 | 142 |
| 162.159.130.71 | 80, 443, 8080 | 162 |
| 162.159.130.71 | 80, 443, 8080 | 162 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b0f:9d99:48d5:93ea:37c0:65e] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:ed27:21e1:279e:c607:7f2a] | 80, 443, 8080 | 3 |
| [2606:4700:99ec:5bf6:5c01:243f:dc1:b321] | 80, 443, 8080 | 3 |
| [2606:4700:839e:68a7:3453:89a:302:ac62] | 80, 443, 8080 | 3 |
| [2606:4700:99ec:6d52:4363:37b4:39ca:b2b6] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:9d99:48d5:93ea:37c0:65e] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:ed27:21e1:279e:c607:7f2a] | 80, 443, 8080 | 3 |
| [2606:4700:99ec:5bf6:5c01:243f:dc1:b321] | 80, 443, 8080 | 3 |
| [2606:4700:839e:68a7:3453:89a:302:ac62] | 80, 443, 8080 | 3 |
| [2606:4700:99ec:6d52:4363:37b4:39ca:b2b6] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:9d99:48d5:93ea:37c0:65e] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:ed27:21e1:279e:c607:7f2a] | 80, 443, 8080 | 3 |
| [2606:4700:99ec:5bf6:5c01:243f:dc1:b321] | 80, 443, 8080 | 3 |
| [2606:4700:839e:68a7:3453:89a:302:ac62] | 80, 443, 8080 | 3 |
| [2606:4700:99ec:6d52:4363:37b4:39ca:b2b6] | 80, 443, 8080 | 3 |

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
