# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-12 19:23:59 +0330

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
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.209.190 | 80, 443, 8080 | 70 |
| 172.67.67.40 | 80, 443, 8080 | 133 |
| 104.17.166.37 | 80, 443, 8080 | 141 |
| 104.21.226.194 | 80, 443, 8080 | 142 |
| 104.17.125.194 | 80, 443, 8080 | 142 |
| 104.18.4.76 | 80, 443, 8080 | 142 |
| 104.19.126.211 | 80, 443, 8080 | 142 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 172.67.144.186 | 80, 443, 8080 | 160 |
| 172.67.68.165 | 80, 443, 8080 | 161 |
| 172.67.77.177 | 80, 443, 8080 | 164 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9640:e766:2980:86b4:aaa5:841b] | 80, 443, 8080 | 3 |
| [2606:4700:4400:a377:51ed:b67b:d4d9:b8b3] | 80, 443, 8080 | 3 |
| [2606:4700:9a9b:3d33:6956:cebb:a0c4:1d35] | 80, 443, 8080 | 3 |
| [2606:4700:9640:e766:2980:86b4:aaa5:841b] | 80, 443, 8080 | 3 |
| [2606:4700:4400:a377:51ed:b67b:d4d9:b8b3] | 80, 443, 8080 | 3 |
| [2606:4700:9a9b:3d33:6956:cebb:a0c4:1d35] | 80, 443, 8080 | 3 |
| [2606:4700:9640:e766:2980:86b4:aaa5:841b] | 80, 443, 8080 | 3 |
| [2606:4700:4400:a377:51ed:b67b:d4d9:b8b3] | 80, 443, 8080 | 3 |
| [2606:4700:9a9b:3d33:6956:cebb:a0c4:1d35] | 80, 443, 8080 | 3 |
| [2606:4700:131:e4c7:957c:228f:21e7:ee33] | 80, 443, 8080 | 13 |
| [2606:4700:131:e4c7:957c:228f:21e7:ee33] | 80, 443, 8080 | 13 |
| [2606:4700:131:e4c7:957c:228f:21e7:ee33] | 80, 443, 8080 | 13 |
| [2606:4700:4400:ebcf:4093:f09f:f526:fc6c] | 80, 443, 8080 | 14 |
| [2606:4700:4400:ebcf:4093:f09f:f526:fc6c] | 80, 443, 8080 | 14 |
| [2606:4700:4400:ebcf:4093:f09f:f526:fc6c] | 80, 443, 8080 | 14 |

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
