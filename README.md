# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-03 15:25:08 +0330

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
| 198.41.208.97 | 80, 443, 8080 | 50 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 172.67.169.162 | 80, 443, 8080 | 132 |
| 172.67.152.160 | 80, 443, 8080 | 136 |
| 172.67.164.202 | 80, 443, 8080 | 137 |
| 104.17.213.105 | 80, 443, 8080 | 143 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.19.67.1 | 80, 443, 8080 | 147 |
| 104.17.31.150 | 80, 443, 8080 | 148 |
| 104.18.8.139 | 80, 443, 8080 | 149 |
| 104.16.90.124 | 80, 443, 8080 | 153 |
| 172.67.75.99 | 80, 443, 8080 | 163 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d93:d7da:aaa1:f85:2874:6190] | 80, 443, 8080 | 3 |
| [2606:4700:13b:2a43:361:17d5:8d64:d5b7] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:5de4:5564:fe4b:b9ee:a9cc] | 80, 443, 8080 | 3 |
| [2606:4700:9ad6:b1f:34e1:e950:350d:ca16] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:d7da:aaa1:f85:2874:6190] | 80, 443, 8080 | 3 |
| [2606:4700:13b:2a43:361:17d5:8d64:d5b7] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:5de4:5564:fe4b:b9ee:a9cc] | 80, 443, 8080 | 3 |
| [2606:4700:9ad6:b1f:34e1:e950:350d:ca16] | 80, 443, 8080 | 3 |
| [2606:4700:8d93:d7da:aaa1:f85:2874:6190] | 80, 443, 8080 | 3 |
| [2606:4700:13b:2a43:361:17d5:8d64:d5b7] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:5de4:5564:fe4b:b9ee:a9cc] | 80, 443, 8080 | 3 |
| [2606:4700:9ad6:b1f:34e1:e950:350d:ca16] | 80, 443, 8080 | 3 |
| [2606:4700:9aeb:646d:8ff:778:214b:27c1] | 80, 443, 8080 | 4 |
| [2606:4700:9aeb:646d:8ff:778:214b:27c1] | 80, 443, 8080 | 4 |
| [2606:4700:9aeb:646d:8ff:778:214b:27c1] | 80, 443, 8080 | 4 |

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
