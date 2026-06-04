# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-05 01:31:11 +0330

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
| 198.41.208.108 | 80, 443, 8080 | 56 |
| 198.41.208.108 | 80, 443, 8080 | 56 |
| 198.41.209.106 | 80, 443, 8080 | 59 |
| 198.41.209.106 | 80, 443, 8080 | 59 |
| 162.159.46.17 | 80, 443, 8080 | 67 |
| 162.159.36.86 | 80, 443, 8080 | 74 |
| 104.17.74.155 | 80, 443, 8080 | 129 |
| 104.18.220.61 | 80, 443, 8080 | 129 |
| 104.17.207.158 | 80, 443, 8080 | 130 |
| 162.159.242.186 | 80, 443, 8080 | 178 |
| 162.159.242.186 | 80, 443, 8080 | 178 |
| 162.159.243.163 | 80, 443, 8080 | 179 |
| 162.159.243.163 | 80, 443, 8080 | 179 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91bc:9184:fcb1:813e:e048:d403] | 80, 443, 8080 | 1 |
| [2606:4700:91bc:9184:fcb1:813e:e048:d403] | 80, 443, 8080 | 1 |
| [2606:4700:91bc:9184:fcb1:813e:e048:d403] | 80, 443, 8080 | 1 |
| [2606:4700:8ca3:a206:316a:e8f4:9b9d:fffa] | 80, 443, 8080 | 3 |
| [2606:4700:8ca3:a206:316a:e8f4:9b9d:fffa] | 80, 443, 8080 | 3 |
| [2606:4700:8ca3:a206:316a:e8f4:9b9d:fffa] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:3311:2e4a:72a0:777b:aa7f] | 80, 443, 8080 | 4 |
| [2606:4700:8d93:3311:2e4a:72a0:777b:aa7f] | 80, 443, 8080 | 4 |
| [2606:4700:8d93:3311:2e4a:72a0:777b:aa7f] | 80, 443, 8080 | 4 |
| [2606:4700:8d93:a3f1:8c60:a23a:1d33:5797] | 80, 443, 8080 | 5 |
| [2606:4700:8d93:a3f1:8c60:a23a:1d33:5797] | 80, 443, 8080 | 5 |
| [2606:4700:8d93:a3f1:8c60:a23a:1d33:5797] | 80, 443, 8080 | 5 |
| [2606:4700:8d98:8b80:2fca:768e:68b0:ca47] | 80, 443, 8080 | 6 |
| [2606:4700:8d98:8b80:2fca:768e:68b0:ca47] | 80, 443, 8080 | 6 |
| [2606:4700:8d98:8b80:2fca:768e:68b0:ca47] | 80, 443, 8080 | 6 |

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
