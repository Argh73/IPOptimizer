# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-25 02:47:43 +0330

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
| 198.41.209.116 | 80, 443, 8080 | 47 |
| 198.41.209.116 | 80, 443, 8080 | 47 |
| 198.41.208.41 | 80, 443, 8080 | 50 |
| 198.41.208.210 | 80, 443, 8080 | 50 |
| 198.41.208.41 | 80, 443, 8080 | 50 |
| 198.41.208.210 | 80, 443, 8080 | 50 |
| 198.41.208.20 | 80, 443, 8080 | 51 |
| 198.41.208.82 | 80, 443, 8080 | 51 |
| 198.41.208.20 | 80, 443, 8080 | 51 |
| 198.41.208.82 | 80, 443, 8080 | 51 |
| 104.17.234.193 | 80, 443, 8080 | 139 |
| 104.16.2.94 | 80, 443, 8080 | 139 |
| 104.16.184.3 | 80, 443, 8080 | 139 |
| 104.19.23.176 | 80, 443, 8080 | 139 |
| 104.17.133.138 | 80, 443, 8080 | 139 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ae6:ebf8:91e8:b1d1:6737:2d90] | 80, 443, 8080 | 3 |
| [2606:4700:2a:631c:2845:7688:8292:a0f0] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:5921:ce3f:5c56:ef22:aa83] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:ebf8:91e8:b1d1:6737:2d90] | 80, 443, 8080 | 3 |
| [2606:4700:2a:631c:2845:7688:8292:a0f0] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:5921:ce3f:5c56:ef22:aa83] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:ebf8:91e8:b1d1:6737:2d90] | 80, 443, 8080 | 3 |
| [2606:4700:2a:631c:2845:7688:8292:a0f0] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:5921:ce3f:5c56:ef22:aa83] | 80, 443, 8080 | 3 |
| [2606:4700:2a:8b29:9482:c7c8:9490:b3d4] | 80, 443, 8080 | 13 |
| [2606:4700:2a:8b29:9482:c7c8:9490:b3d4] | 80, 443, 8080 | 13 |
| [2606:4700:2a:8b29:9482:c7c8:9490:b3d4] | 80, 443, 8080 | 13 |
| [2606:4700:8ca8:c991:5f3:f7d0:dcc9:5dc7] | 80, 443, 8080 | 138 |
| [2606:4700:8ca8:c991:5f3:f7d0:dcc9:5dc7] | 80, 443, 8080 | 138 |
| [2606:4700:8ca8:c991:5f3:f7d0:dcc9:5dc7] | 80, 443, 8080 | 138 |

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
