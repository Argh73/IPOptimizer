# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-27 13:56:12 +0330

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
| 198.41.209.212 | 80, 443, 8080 | 53 |
| 198.41.209.212 | 80, 443, 8080 | 53 |
| 198.41.209.208 | 80, 443, 8080 | 57 |
| 198.41.209.89 | 80, 443, 8080 | 57 |
| 198.41.209.208 | 80, 443, 8080 | 57 |
| 198.41.209.89 | 80, 443, 8080 | 57 |
| 198.41.209.153 | 80, 443, 8080 | 58 |
| 198.41.209.153 | 80, 443, 8080 | 58 |
| 198.41.209.194 | 80, 443, 8080 | 62 |
| 198.41.209.194 | 80, 443, 8080 | 62 |
| 104.19.44.121 | 80, 443, 8080 | 143 |
| 104.16.84.72 | 80, 443, 8080 | 145 |
| 104.24.90.148 | 80, 443, 8080 | 166 |
| 104.24.148.78 | 80, 443, 8080 | 167 |
| 104.17.192.28 | 80, 443, 8080 | 169 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d77:9aa7:c654:7ea3:d27e:828b] | 80, 443, 8080 | 3 |
| [2606:4700:135:1384:f469:9838:61d2:e06c] | 80, 443, 8080 | 3 |
| [2606:4700:91b9:db77:7ec0:c69:c45d:1dd0] | 80, 443, 8080 | 3 |
| [2606:4700:9760:c71:441e:49a2:b5cf:5675] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:9aa7:c654:7ea3:d27e:828b] | 80, 443, 8080 | 3 |
| [2606:4700:135:1384:f469:9838:61d2:e06c] | 80, 443, 8080 | 3 |
| [2606:4700:91b9:db77:7ec0:c69:c45d:1dd0] | 80, 443, 8080 | 3 |
| [2606:4700:9760:c71:441e:49a2:b5cf:5675] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:9aa7:c654:7ea3:d27e:828b] | 80, 443, 8080 | 3 |
| [2606:4700:135:1384:f469:9838:61d2:e06c] | 80, 443, 8080 | 3 |
| [2606:4700:91b9:db77:7ec0:c69:c45d:1dd0] | 80, 443, 8080 | 3 |
| [2606:4700:9760:c71:441e:49a2:b5cf:5675] | 80, 443, 8080 | 3 |
| [2606:4700:83b6:ab28:8a64:9d71:2845:a483] | 80, 443, 8080 | 170 |
| [2606:4700:83b6:ab28:8a64:9d71:2845:a483] | 80, 443, 8080 | 170 |
| [2606:4700:83b6:ab28:8a64:9d71:2845:a483] | 80, 443, 8080 | 170 |

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
