# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-25 02:07:27 +0330

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
| 198.41.208.49 | 80, 443, 8080 | 49 |
| 198.41.209.68 | 80, 443, 8080 | 51 |
| 198.41.208.69 | 80, 443, 8080 | 52 |
| 198.41.208.18 | 80, 443, 8080 | 52 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 172.67.148.209 | 80, 443, 8080 | 136 |
| 104.19.124.251 | 80, 443, 8080 | 138 |
| 104.17.205.188 | 80, 443, 8080 | 138 |
| 104.19.14.183 | 80, 443, 8080 | 139 |
| 104.18.87.20 | 80, 443, 8080 | 139 |
| 104.16.214.157 | 80, 443, 8080 | 139 |
| 172.67.251.117 | 80, 443, 8080 | 145 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d7d:2a95:548d:6082:af98:8544] | 80, 443, 8080 | 3 |
| [2606:4700:27:2f38:bf43:d41b:c604:2aab] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:2a95:548d:6082:af98:8544] | 80, 443, 8080 | 3 |
| [2606:4700:27:2f38:bf43:d41b:c604:2aab] | 80, 443, 8080 | 3 |
| [2606:4700:8d7d:2a95:548d:6082:af98:8544] | 80, 443, 8080 | 3 |
| [2606:4700:27:2f38:bf43:d41b:c604:2aab] | 80, 443, 8080 | 3 |
| [2606:4700:8ca4:2be:58ab:fb82:998f:8ed] | 80, 443, 8080 | 135 |
| [2606:4700:8ca4:2be:58ab:fb82:998f:8ed] | 80, 443, 8080 | 135 |
| [2606:4700:8ca4:2be:58ab:fb82:998f:8ed] | 80, 443, 8080 | 135 |
| [2606:4700:90c1:529d:50e:2505:39f9:f6b1] | 80, 443, 8080 | 153 |
| [2606:4700:90c1:529d:50e:2505:39f9:f6b1] | 80, 443, 8080 | 153 |
| [2606:4700:90c1:529d:50e:2505:39f9:f6b1] | 80, 443, 8080 | 153 |
| [2606:4700:90c1:d9e:d881:bd6b:8cfe:1199] | 80, 443, 8080 | 157 |
| [2606:4700:90c1:d9e:d881:bd6b:8cfe:1199] | 80, 443, 8080 | 157 |
| [2606:4700:90c1:d9e:d881:bd6b:8cfe:1199] | 80, 443, 8080 | 157 |

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
