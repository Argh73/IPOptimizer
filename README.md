# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-16 02:03:38 +0330

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
| 198.41.222.245 | 80, 443, 8080 | 70 |
| 198.41.222.245 | 80, 443, 8080 | 70 |
| 198.41.222.245 | 80, 443, 8080 | 70 |
| 162.159.46.154 | 80, 443, 8080 | 71 |
| 162.159.46.154 | 80, 443, 8080 | 71 |
| 162.159.46.154 | 80, 443, 8080 | 71 |
| 104.19.121.64 | 80, 443, 8080 | 129 |
| 104.19.121.64 | 80, 443, 8080 | 129 |
| 104.19.121.64 | 80, 443, 8080 | 129 |
| 104.16.74.80 | 80, 443, 8080 | 130 |
| 104.16.204.40 | 80, 443, 8080 | 130 |
| 104.16.74.80 | 80, 443, 8080 | 130 |
| 104.16.204.40 | 80, 443, 8080 | 130 |
| 104.16.74.80 | 80, 443, 8080 | 130 |
| 104.16.204.40 | 80, 443, 8080 | 130 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d77:5b75:72a2:ef4c:992f:ab86] | 80, 443, 8080 | 0 |
| [2606:4700:16:2916:7c91:c0e1:fef7:c91c] | 80, 443, 8080 | 0 |
| [2606:4700:9a91:d027:183f:2476:e0ec:e667] | 80, 443, 8080 | 0 |
| [2606:4700:8de0:e9b0:a3d6:1bd1:96a:a85e] | 80, 443, 8080 | 0 |
| [2606:4700:8d77:5b75:72a2:ef4c:992f:ab86] | 80, 443, 8080 | 0 |
| [2606:4700:16:2916:7c91:c0e1:fef7:c91c] | 80, 443, 8080 | 0 |
| [2606:4700:9a91:d027:183f:2476:e0ec:e667] | 80, 443, 8080 | 0 |
| [2606:4700:8de0:e9b0:a3d6:1bd1:96a:a85e] | 80, 443, 8080 | 0 |
| [2606:4700:8d77:5b75:72a2:ef4c:992f:ab86] | 80, 443, 8080 | 0 |
| [2606:4700:16:2916:7c91:c0e1:fef7:c91c] | 80, 443, 8080 | 0 |
| [2606:4700:9a91:d027:183f:2476:e0ec:e667] | 80, 443, 8080 | 0 |
| [2606:4700:8de0:e9b0:a3d6:1bd1:96a:a85e] | 80, 443, 8080 | 0 |
| [2606:4700:9a91:d30c:d111:9559:37cc:104f] | 80, 443, 8080 | 1 |
| [2606:4700:9a91:d30c:d111:9559:37cc:104f] | 80, 443, 8080 | 1 |
| [2606:4700:9a91:d30c:d111:9559:37cc:104f] | 80, 443, 8080 | 1 |

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
