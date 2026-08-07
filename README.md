# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-07 04:26:20 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.214 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.208.179 | 80, 443, 8080 | 54 |
| 198.41.208.179 | 80, 443, 8080 | 54 |
| 198.41.208.153 | 80, 443, 8080 | 55 |
| 198.41.208.153 | 80, 443, 8080 | 55 |
| 198.41.208.188 | 80, 443, 8080 | 56 |
| 198.41.208.188 | 80, 443, 8080 | 56 |
| 162.159.36.95 | 80, 443, 8080 | 66 |
| 104.19.95.24 | 80, 443, 8080 | 158 |
| 172.67.69.22 | 80, 443, 8080 | 163 |
| 104.24.166.226 | 80, 443, 8080 | 164 |
| 104.24.250.135 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:99ed:a7e5:c74c:9722:b5ce:c34f] | 80, 443, 8080 | 0 |
| [2606:4700:9b01:290a:6fcd:58e4:6180:3a8e] | 80, 443, 8080 | 0 |
| [2606:4700:99e2:b24d:e114:fe0c:aefb:d206] | 80, 443, 8080 | 0 |
| [2606:4700:99ed:a7e5:c74c:9722:b5ce:c34f] | 80, 443, 8080 | 0 |
| [2606:4700:9b01:290a:6fcd:58e4:6180:3a8e] | 80, 443, 8080 | 0 |
| [2606:4700:99e2:b24d:e114:fe0c:aefb:d206] | 80, 443, 8080 | 0 |
| [2606:4700:99ed:a7e5:c74c:9722:b5ce:c34f] | 80, 443, 8080 | 0 |
| [2606:4700:9b01:290a:6fcd:58e4:6180:3a8e] | 80, 443, 8080 | 0 |
| [2606:4700:99e2:b24d:e114:fe0c:aefb:d206] | 80, 443, 8080 | 0 |
| [2606:4700:9645:864b:6ff4:affd:fa64:7cec] | 80, 443, 8080 | 1 |
| [2606:4700:9645:864b:6ff4:affd:fa64:7cec] | 80, 443, 8080 | 1 |
| [2606:4700:9645:864b:6ff4:affd:fa64:7cec] | 80, 443, 8080 | 1 |
| [2606:4700:83b5:3107:4c41:bbe6:cca3:f5b1] | 80, 443, 8080 | 146 |
| [2606:4700:83b5:3107:4c41:bbe6:cca3:f5b1] | 80, 443, 8080 | 146 |
| [2606:4700:83b5:3107:4c41:bbe6:cca3:f5b1] | 80, 443, 8080 | 146 |

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
