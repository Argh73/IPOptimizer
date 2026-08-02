# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-03 00:54:13 +0330

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
| 198.41.208.103 | 80, 443, 8080 | 51 |
| 198.41.208.113 | 80, 443, 8080 | 51 |
| 198.41.208.103 | 80, 443, 8080 | 51 |
| 198.41.208.113 | 80, 443, 8080 | 51 |
| 198.41.208.139 | 80, 443, 8080 | 52 |
| 198.41.208.131 | 80, 443, 8080 | 52 |
| 198.41.208.139 | 80, 443, 8080 | 52 |
| 198.41.208.131 | 80, 443, 8080 | 52 |
| 198.41.208.165 | 80, 443, 8080 | 68 |
| 198.41.208.165 | 80, 443, 8080 | 68 |
| 104.17.100.161 | 80, 443, 8080 | 139 |
| 104.21.227.227 | 80, 443, 8080 | 139 |
| 104.17.73.107 | 80, 443, 8080 | 139 |
| 104.19.142.31 | 80, 443, 8080 | 139 |
| 104.17.113.175 | 80, 443, 8080 | 140 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a65:f3f1:fb1f:36d1:c02e:a13f] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:3a0a:c3f:d7e6:cabf:8aa1] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:3403:9822:efbd:d938:b857] | 80, 443, 8080 | 3 |
| [2606:4700:976b:5b03:5a98:6b63:dc9e:2a90] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:a058:5075:8f9f:4611:599a] | 80, 443, 8080 | 3 |
| [2606:4700:9a65:f3f1:fb1f:36d1:c02e:a13f] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:3a0a:c3f:d7e6:cabf:8aa1] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:3403:9822:efbd:d938:b857] | 80, 443, 8080 | 3 |
| [2606:4700:976b:5b03:5a98:6b63:dc9e:2a90] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:a058:5075:8f9f:4611:599a] | 80, 443, 8080 | 3 |
| [2606:4700:9a65:f3f1:fb1f:36d1:c02e:a13f] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:3a0a:c3f:d7e6:cabf:8aa1] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:3403:9822:efbd:d938:b857] | 80, 443, 8080 | 3 |
| [2606:4700:976b:5b03:5a98:6b63:dc9e:2a90] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:a058:5075:8f9f:4611:599a] | 80, 443, 8080 | 3 |

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
