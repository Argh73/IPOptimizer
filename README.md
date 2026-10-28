# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-28 16:51:17 +0330

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
| 198.41.208.250 | 80, 443, 8080 | 52 |
| 198.41.208.250 | 80, 443, 8080 | 52 |
| 198.41.208.123 | 80, 443, 8080 | 53 |
| 198.41.208.123 | 80, 443, 8080 | 53 |
| 198.41.209.74 | 80, 443, 8080 | 56 |
| 198.41.209.74 | 80, 443, 8080 | 56 |
| 198.41.209.142 | 80, 443, 8080 | 66 |
| 198.41.209.142 | 80, 443, 8080 | 66 |
| 104.19.72.163 | 80, 443, 8080 | 141 |
| 104.17.65.134 | 80, 443, 8080 | 142 |
| 104.16.129.52 | 80, 443, 8080 | 142 |
| 104.19.80.241 | 80, 443, 8080 | 143 |
| 104.19.74.244 | 80, 443, 8080 | 143 |
| 172.67.230.146 | 80, 443, 8080 | 166 |
| 172.67.230.146 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b09:17f8:78ff:9090:53fe:5fd0] | 80, 443, 8080 | 3 |
| [2606:4700:d0:37ff:350d:8dc0:dee7:e069] | 80, 443, 8080 | 3 |
| [2606:4700:3008:7a72:8622:eed1:acc5:a79d] | 80, 443, 8080 | 3 |
| [2606:4700:3008:d10d:7d26:fa3f:a8e1:dfb2] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:17f8:78ff:9090:53fe:5fd0] | 80, 443, 8080 | 3 |
| [2606:4700:d0:37ff:350d:8dc0:dee7:e069] | 80, 443, 8080 | 3 |
| [2606:4700:3008:7a72:8622:eed1:acc5:a79d] | 80, 443, 8080 | 3 |
| [2606:4700:3008:d10d:7d26:fa3f:a8e1:dfb2] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:17f8:78ff:9090:53fe:5fd0] | 80, 443, 8080 | 3 |
| [2606:4700:d0:37ff:350d:8dc0:dee7:e069] | 80, 443, 8080 | 3 |
| [2606:4700:3008:7a72:8622:eed1:acc5:a79d] | 80, 443, 8080 | 3 |
| [2606:4700:3008:d10d:7d26:fa3f:a8e1:dfb2] | 80, 443, 8080 | 3 |
| [2606:4700:440c:2084:39c3:d0e3:c7eb:a5e9] | 80, 443, 8080 | 13 |
| [2606:4700:440c:2084:39c3:d0e3:c7eb:a5e9] | 80, 443, 8080 | 13 |
| [2606:4700:440c:2084:39c3:d0e3:c7eb:a5e9] | 80, 443, 8080 | 13 |

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
