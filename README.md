# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-27 15:49:08 +0330

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
| 198.41.209.94 | 80, 443, 8080 | 109 |
| 198.41.209.94 | 80, 443, 8080 | 109 |
| 104.17.7.189 | 80, 443, 8080 | 149 |
| 198.41.209.189 | 80, 443, 8080 | 150 |
| 198.41.209.189 | 80, 443, 8080 | 150 |
| 104.19.30.164 | 80, 443, 8080 | 151 |
| 104.16.10.178 | 80, 443, 8080 | 152 |
| 172.67.130.64 | 80, 443, 8080 | 153 |
| 104.19.17.74 | 80, 443, 8080 | 153 |
| 162.159.160.16 | 80, 443, 8080 | 157 |
| 162.159.160.16 | 80, 443, 8080 | 157 |
| 162.159.133.1 | 80, 443, 8080 | 164 |
| 162.159.133.1 | 80, 443, 8080 | 164 |
| 162.159.135.12 | 80, 443, 8080 | 165 |
| 162.159.135.12 | 80, 443, 8080 | 165 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9646:6838:9b19:631b:92b9:76fa] | 80, 443, 8080 | 3 |
| [2606:4700:90ce:8c7:b32d:3a85:6f50:43de] | 80, 443, 8080 | 3 |
| [2606:4700:13b:99e8:760a:9b78:588c:4e16] | 80, 443, 8080 | 3 |
| [2606:4700:90ce:e5a7:6fd5:58f3:e69b:c32b] | 80, 443, 8080 | 3 |
| [2606:4700:8d95:8db1:69cb:fc4d:ca13:611f] | 80, 443, 8080 | 3 |
| [2606:4700:9646:6838:9b19:631b:92b9:76fa] | 80, 443, 8080 | 3 |
| [2606:4700:90ce:8c7:b32d:3a85:6f50:43de] | 80, 443, 8080 | 3 |
| [2606:4700:13b:99e8:760a:9b78:588c:4e16] | 80, 443, 8080 | 3 |
| [2606:4700:90ce:e5a7:6fd5:58f3:e69b:c32b] | 80, 443, 8080 | 3 |
| [2606:4700:8d95:8db1:69cb:fc4d:ca13:611f] | 80, 443, 8080 | 3 |
| [2606:4700:9646:6838:9b19:631b:92b9:76fa] | 80, 443, 8080 | 3 |
| [2606:4700:90ce:8c7:b32d:3a85:6f50:43de] | 80, 443, 8080 | 3 |
| [2606:4700:13b:99e8:760a:9b78:588c:4e16] | 80, 443, 8080 | 3 |
| [2606:4700:90ce:e5a7:6fd5:58f3:e69b:c32b] | 80, 443, 8080 | 3 |
| [2606:4700:8d95:8db1:69cb:fc4d:ca13:611f] | 80, 443, 8080 | 3 |

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
