# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-24 15:34:33 +0330

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
| 198.41.209.144 | 80, 443, 8080 | 52 |
| 198.41.209.144 | 80, 443, 8080 | 52 |
| 198.41.208.81 | 80, 443, 8080 | 83 |
| 198.41.208.81 | 80, 443, 8080 | 83 |
| 104.19.37.155 | 80, 443, 8080 | 141 |
| 198.41.209.195 | 80, 443, 8080 | 142 |
| 104.16.17.143 | 80, 443, 8080 | 142 |
| 198.41.209.195 | 80, 443, 8080 | 142 |
| 104.19.86.130 | 80, 443, 8080 | 143 |
| 104.16.246.230 | 80, 443, 8080 | 144 |
| 104.19.30.145 | 80, 443, 8080 | 149 |
| 162.159.134.37 | 80, 443, 8080 | 164 |
| 162.159.134.37 | 80, 443, 8080 | 164 |
| 162.159.137.228 | 80, 443, 8080 | 165 |
| 162.159.137.228 | 80, 443, 8080 | 165 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:99e0:cf96:1547:5e58:efaa:cea5] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:5b6c:2242:6973:efe5:2cf3] | 80, 443, 8080 | 3 |
| [2606:4700:91b3:71a3:8e:3cf3:7bc3:2722] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:8a45:b816:6b2:177:8862] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:cf96:1547:5e58:efaa:cea5] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:5b6c:2242:6973:efe5:2cf3] | 80, 443, 8080 | 3 |
| [2606:4700:91b3:71a3:8e:3cf3:7bc3:2722] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:8a45:b816:6b2:177:8862] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:cf96:1547:5e58:efaa:cea5] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:5b6c:2242:6973:efe5:2cf3] | 80, 443, 8080 | 3 |
| [2606:4700:91b3:71a3:8e:3cf3:7bc3:2722] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:8a45:b816:6b2:177:8862] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:d2f5:e721:6ae7:6752:5ac3] | 80, 443, 8080 | 5 |
| [2606:4700:9ae6:d2f5:e721:6ae7:6752:5ac3] | 80, 443, 8080 | 5 |
| [2606:4700:9ae6:d2f5:e721:6ae7:6752:5ac3] | 80, 443, 8080 | 5 |

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
