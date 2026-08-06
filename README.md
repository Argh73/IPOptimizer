# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-06 12:51:44 +0330

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
| 198.41.208.206 | 80, 443, 8080 | 58 |
| 198.41.208.206 | 80, 443, 8080 | 58 |
| 198.41.223.118 | 80, 443, 8080 | 65 |
| 198.41.208.28 | 80, 443, 8080 | 67 |
| 198.41.208.28 | 80, 443, 8080 | 67 |
| 162.159.36.76 | 80, 443, 8080 | 73 |
| 198.41.209.71 | 80, 443, 8080 | 103 |
| 198.41.209.71 | 80, 443, 8080 | 103 |
| 104.16.70.236 | 80, 443, 8080 | 145 |
| 198.41.209.2 | 80, 443, 8080 | 149 |
| 198.41.209.2 | 80, 443, 8080 | 149 |
| 104.18.111.62 | 80, 443, 8080 | 150 |
| 104.17.0.245 | 80, 443, 8080 | 150 |
| 198.41.208.5 | 80, 443, 8080 | 153 |
| 198.41.208.5 | 80, 443, 8080 | 153 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b06:bbe6:9c1f:5803:a9c:7ca7] | 80, 443, 8080 | 0 |
| [2606:4700:9ae6:7a38:dc66:eff:6ae:7fdf] | 80, 443, 8080 | 0 |
| [2606:4700:90d0:6f92:1c9c:839d:99fd:11fa] | 80, 443, 8080 | 0 |
| [2606:4700:440e:99ee:4ca4:7d8b:d503:d9da] | 80, 443, 8080 | 0 |
| [2606:4700:9b06:bbe6:9c1f:5803:a9c:7ca7] | 80, 443, 8080 | 0 |
| [2606:4700:9ae6:7a38:dc66:eff:6ae:7fdf] | 80, 443, 8080 | 0 |
| [2606:4700:90d0:6f92:1c9c:839d:99fd:11fa] | 80, 443, 8080 | 0 |
| [2606:4700:440e:99ee:4ca4:7d8b:d503:d9da] | 80, 443, 8080 | 0 |
| [2606:4700:9b06:bbe6:9c1f:5803:a9c:7ca7] | 80, 443, 8080 | 0 |
| [2606:4700:9ae6:7a38:dc66:eff:6ae:7fdf] | 80, 443, 8080 | 0 |
| [2606:4700:90d0:6f92:1c9c:839d:99fd:11fa] | 80, 443, 8080 | 0 |
| [2606:4700:440e:99ee:4ca4:7d8b:d503:d9da] | 80, 443, 8080 | 0 |
| [2606:4700:440e:a91e:a324:b7b0:a071:225b] | 80, 443, 8080 | 1 |
| [2606:4700:440e:a91e:a324:b7b0:a071:225b] | 80, 443, 8080 | 1 |
| [2606:4700:440e:a91e:a324:b7b0:a071:225b] | 80, 443, 8080 | 1 |

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
