# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-28 07:54:58 +0330

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
| 198.41.208.112 | 80, 443, 8080 | 46 |
| 198.41.208.112 | 80, 443, 8080 | 46 |
| 198.41.208.101 | 80, 443, 8080 | 47 |
| 198.41.208.145 | 80, 443, 8080 | 47 |
| 198.41.208.101 | 80, 443, 8080 | 47 |
| 198.41.208.145 | 80, 443, 8080 | 47 |
| 198.41.208.140 | 80, 443, 8080 | 48 |
| 198.41.208.140 | 80, 443, 8080 | 48 |
| 198.41.208.14 | 80, 443, 8080 | 50 |
| 198.41.208.14 | 80, 443, 8080 | 50 |
| 162.159.46.211 | 80, 443, 8080 | 92 |
| 104.17.113.6 | 80, 443, 8080 | 139 |
| 104.17.251.222 | 80, 443, 8080 | 143 |
| 104.16.199.118 | 80, 443, 8080 | 143 |
| 104.16.110.112 | 80, 443, 8080 | 144 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9768:a1b3:e6dd:c07:d373:62ae] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:305f:3e4c:e31:eb8c:b5b8] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:82f4:ab60:b018:899b:8bba] | 80, 443, 8080 | 3 |
| [2606:4700:9768:a1b3:e6dd:c07:d373:62ae] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:305f:3e4c:e31:eb8c:b5b8] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:82f4:ab60:b018:899b:8bba] | 80, 443, 8080 | 3 |
| [2606:4700:9768:a1b3:e6dd:c07:d373:62ae] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:305f:3e4c:e31:eb8c:b5b8] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:82f4:ab60:b018:899b:8bba] | 80, 443, 8080 | 3 |
| [2606:4700:8caa:a20c:b7e6:b2f8:3b51:3f40] | 80, 443, 8080 | 140 |
| [2606:4700:8caa:a20c:b7e6:b2f8:3b51:3f40] | 80, 443, 8080 | 140 |
| [2606:4700:8caa:a20c:b7e6:b2f8:3b51:3f40] | 80, 443, 8080 | 140 |
| [2606:4700:8caa:2f84:884d:a6fb:443a:3aeb] | 80, 443, 8080 | 141 |
| [2606:4700:8caa:2f84:884d:a6fb:443a:3aeb] | 80, 443, 8080 | 141 |
| [2606:4700:8caa:2f84:884d:a6fb:443a:3aeb] | 80, 443, 8080 | 141 |

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
