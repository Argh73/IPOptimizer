# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-13 13:24:35 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.192 | 80, 443, 8080 | 52 |
| 198.41.209.192 | 80, 443, 8080 | 52 |
| 198.41.209.180 | 80, 443, 8080 | 53 |
| 198.41.209.180 | 80, 443, 8080 | 53 |
| 198.41.208.46 | 80, 443, 8080 | 54 |
| 198.41.208.46 | 80, 443, 8080 | 54 |
| 198.41.208.237 | 80, 443, 8080 | 56 |
| 198.41.208.237 | 80, 443, 8080 | 56 |
| 198.41.223.133 | 80, 443, 8080 | 69 |
| 198.41.223.254 | 80, 443, 8080 | 76 |
| 162.159.253.164 | 80, 443, 8080 | 142 |
| 162.159.250.126 | 80, 443, 8080 | 143 |
| 104.16.150.254 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9760:7d1a:8e7e:3486:d7b9:df96] | 80, 443, 8080 | 0 |
| [2606:4700:9760:cb0d:5801:2544:502b:9161] | 80, 443, 8080 | 0 |
| [2606:4700:90d5:ac1e:a0c2:af0c:7f17:2009] | 80, 443, 8080 | 0 |
| [2606:4700:3004:e2f9:deb0:980a:d009:5576] | 80, 443, 8080 | 0 |
| [2606:4700:9760:7d1a:8e7e:3486:d7b9:df96] | 80, 443, 8080 | 0 |
| [2606:4700:9760:cb0d:5801:2544:502b:9161] | 80, 443, 8080 | 0 |
| [2606:4700:90d5:ac1e:a0c2:af0c:7f17:2009] | 80, 443, 8080 | 0 |
| [2606:4700:3004:e2f9:deb0:980a:d009:5576] | 80, 443, 8080 | 0 |
| [2606:4700:9760:7d1a:8e7e:3486:d7b9:df96] | 80, 443, 8080 | 0 |
| [2606:4700:9760:cb0d:5801:2544:502b:9161] | 80, 443, 8080 | 0 |
| [2606:4700:90d5:ac1e:a0c2:af0c:7f17:2009] | 80, 443, 8080 | 0 |
| [2606:4700:3004:e2f9:deb0:980a:d009:5576] | 80, 443, 8080 | 0 |
| [2606:4700:300b:a721:6cb7:18e4:e5a7:abc7] | 80, 443, 8080 | 1 |
| [2606:4700:300b:a721:6cb7:18e4:e5a7:abc7] | 80, 443, 8080 | 1 |
| [2606:4700:300b:a721:6cb7:18e4:e5a7:abc7] | 80, 443, 8080 | 1 |

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
