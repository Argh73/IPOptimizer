# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-22 01:07:57 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.208.167 | 80, 443, 8080 | 53 |
| 198.41.208.167 | 80, 443, 8080 | 53 |
| 198.41.209.196 | 80, 443, 8080 | 54 |
| 198.41.209.196 | 80, 443, 8080 | 54 |
| 198.41.208.75 | 80, 443, 8080 | 55 |
| 198.41.208.75 | 80, 443, 8080 | 55 |
| 198.41.208.159 | 80, 443, 8080 | 56 |
| 198.41.208.159 | 80, 443, 8080 | 56 |
| 162.159.247.170 | 80, 443, 8080 | 138 |
| 104.16.88.39 | 80, 443, 8080 | 138 |
| 104.19.242.108 | 80, 443, 8080 | 138 |
| 104.19.250.116 | 80, 443, 8080 | 139 |
| 104.17.7.181 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a6e:732e:547f:5de8:85c7:65a] | 80, 443, 8080 | 0 |
| [2606:4700:976c:b74b:36bc:199d:5817:2459] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:4c2d:4305:abd4:661d:67a5] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:17fc:ab21:725d:7fbd:41d5] | 80, 443, 8080 | 0 |
| [2606:4700:9a6e:732e:547f:5de8:85c7:65a] | 80, 443, 8080 | 0 |
| [2606:4700:976c:b74b:36bc:199d:5817:2459] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:4c2d:4305:abd4:661d:67a5] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:17fc:ab21:725d:7fbd:41d5] | 80, 443, 8080 | 0 |
| [2606:4700:9a6e:732e:547f:5de8:85c7:65a] | 80, 443, 8080 | 0 |
| [2606:4700:976c:b74b:36bc:199d:5817:2459] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:4c2d:4305:abd4:661d:67a5] | 80, 443, 8080 | 0 |
| [2606:4700:9a9f:17fc:ab21:725d:7fbd:41d5] | 80, 443, 8080 | 0 |
| [2606:4700:976c:f094:6fde:2ffc:b2bf:6f31] | 80, 443, 8080 | 1 |
| [2606:4700:976c:f094:6fde:2ffc:b2bf:6f31] | 80, 443, 8080 | 1 |
| [2606:4700:976c:f094:6fde:2ffc:b2bf:6f31] | 80, 443, 8080 | 1 |

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
