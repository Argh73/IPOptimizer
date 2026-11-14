# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-14 17:13:55 +0330

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
| 104.18.208.219 | 80, 443, 8080 | 141 |
| 104.17.30.205 | 80, 443, 8080 | 141 |
| 104.18.240.157 | 80, 443, 8080 | 141 |
| 104.19.88.125 | 80, 443, 8080 | 142 |
| 104.19.87.188 | 80, 443, 8080 | 142 |
| 162.159.160.59 | 80, 443, 8080 | 151 |
| 162.159.160.59 | 80, 443, 8080 | 151 |
| 162.159.152.180 | 80, 443, 8080 | 164 |
| 162.159.152.180 | 80, 443, 8080 | 164 |
| 162.159.137.212 | 80, 443, 8080 | 165 |
| 162.159.137.212 | 80, 443, 8080 | 165 |
| 162.159.135.201 | 80, 443, 8080 | 166 |
| 162.159.135.201 | 80, 443, 8080 | 166 |
| 162.159.133.17 | 80, 443, 8080 | 168 |
| 162.159.133.17 | 80, 443, 8080 | 168 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dee:484a:330:ca3a:ee6a:1c0b] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:7f7a:cb3b:949d:ccd6:721a] | 80, 443, 8080 | 3 |
| [2606:4700:964a:afd5:3d87:1a24:ef8f:3360] | 80, 443, 8080 | 3 |
| [2606:4700:964a:79aa:a9ab:16c9:b7fa:8f14] | 80, 443, 8080 | 3 |
| [2606:4700:13d:7a51:5918:e24a:6305:d312] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:484a:330:ca3a:ee6a:1c0b] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:7f7a:cb3b:949d:ccd6:721a] | 80, 443, 8080 | 3 |
| [2606:4700:964a:afd5:3d87:1a24:ef8f:3360] | 80, 443, 8080 | 3 |
| [2606:4700:964a:79aa:a9ab:16c9:b7fa:8f14] | 80, 443, 8080 | 3 |
| [2606:4700:13d:7a51:5918:e24a:6305:d312] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:484a:330:ca3a:ee6a:1c0b] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:7f7a:cb3b:949d:ccd6:721a] | 80, 443, 8080 | 3 |
| [2606:4700:964a:afd5:3d87:1a24:ef8f:3360] | 80, 443, 8080 | 3 |
| [2606:4700:964a:79aa:a9ab:16c9:b7fa:8f14] | 80, 443, 8080 | 3 |
| [2606:4700:13d:7a51:5918:e24a:6305:d312] | 80, 443, 8080 | 3 |

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
