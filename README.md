# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-11 01:04:25 +0330

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
| 198.41.209.192 | 80, 443, 8080 | 53 |
| 198.41.209.81 | 80, 443, 8080 | 53 |
| 198.41.209.192 | 80, 443, 8080 | 53 |
| 198.41.209.81 | 80, 443, 8080 | 53 |
| 198.41.209.251 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.209.251 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.209.145 | 80, 443, 8080 | 59 |
| 198.41.209.145 | 80, 443, 8080 | 59 |
| 104.18.96.92 | 80, 443, 8080 | 138 |
| 104.17.98.92 | 80, 443, 8080 | 138 |
| 104.17.175.191 | 80, 443, 8080 | 139 |
| 104.18.169.108 | 80, 443, 8080 | 139 |
| 104.19.38.52 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90dc:e414:991f:ae0e:63cb:4e3] | 80, 443, 8080 | 0 |
| [2606:4700:90cc:227f:4d69:750c:6f5e:2fb] | 80, 443, 8080 | 0 |
| [2606:4700:90ca:ae79:26bf:851d:b029:6a2f] | 80, 443, 8080 | 0 |
| [2606:4700:90dc:e414:991f:ae0e:63cb:4e3] | 80, 443, 8080 | 0 |
| [2606:4700:90cc:227f:4d69:750c:6f5e:2fb] | 80, 443, 8080 | 0 |
| [2606:4700:90ca:ae79:26bf:851d:b029:6a2f] | 80, 443, 8080 | 0 |
| [2606:4700:90dc:e414:991f:ae0e:63cb:4e3] | 80, 443, 8080 | 0 |
| [2606:4700:90cc:227f:4d69:750c:6f5e:2fb] | 80, 443, 8080 | 0 |
| [2606:4700:90ca:ae79:26bf:851d:b029:6a2f] | 80, 443, 8080 | 0 |
| [2606:4700:9ad2:98a4:9b37:4988:fba6:ee3b] | 80, 443, 8080 | 1 |
| [2606:4700:9ad2:6ab1:899a:30e9:57f:ea4] | 80, 443, 8080 | 1 |
| [2606:4700:9ad2:98a4:9b37:4988:fba6:ee3b] | 80, 443, 8080 | 1 |
| [2606:4700:9ad2:6ab1:899a:30e9:57f:ea4] | 80, 443, 8080 | 1 |
| [2606:4700:9ad2:98a4:9b37:4988:fba6:ee3b] | 80, 443, 8080 | 1 |
| [2606:4700:9ad2:6ab1:899a:30e9:57f:ea4] | 80, 443, 8080 | 1 |

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
