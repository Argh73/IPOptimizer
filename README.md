# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-10 18:37:37 +0330

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
| 198.41.209.247 | 80, 443, 8080 | 52 |
| 198.41.209.247 | 80, 443, 8080 | 52 |
| 198.41.208.176 | 80, 443, 8080 | 53 |
| 198.41.208.176 | 80, 443, 8080 | 53 |
| 198.41.209.219 | 80, 443, 8080 | 81 |
| 198.41.209.166 | 80, 443, 8080 | 81 |
| 198.41.209.219 | 80, 443, 8080 | 81 |
| 198.41.209.166 | 80, 443, 8080 | 81 |
| 198.41.209.172 | 80, 443, 8080 | 108 |
| 198.41.209.172 | 80, 443, 8080 | 108 |
| 198.41.211.152 | 80, 443, 8080 | 111 |
| 104.16.100.130 | 80, 443, 8080 | 141 |
| 104.16.69.236 | 80, 443, 8080 | 142 |
| 104.17.220.85 | 80, 443, 8080 | 142 |
| 104.19.230.236 | 80, 443, 8080 | 142 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:24:9917:b7a3:a24a:52a5:f9d3] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:901b:d6bf:1a95:8d92:1290] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:c24c:2060:aea8:9b94:d8c3] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:dfca:8ed6:ef24:8458:da21] | 80, 443, 8080 | 3 |
| [2606:4700:24:9917:b7a3:a24a:52a5:f9d3] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:901b:d6bf:1a95:8d92:1290] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:c24c:2060:aea8:9b94:d8c3] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:dfca:8ed6:ef24:8458:da21] | 80, 443, 8080 | 3 |
| [2606:4700:24:9917:b7a3:a24a:52a5:f9d3] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:901b:d6bf:1a95:8d92:1290] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:c24c:2060:aea8:9b94:d8c3] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:dfca:8ed6:ef24:8458:da21] | 80, 443, 8080 | 3 |
| [2606:4700:24:ecc7:3c5e:d8bf:9242:a8e6] | 80, 443, 8080 | 13 |
| [2606:4700:24:ecc7:3c5e:d8bf:9242:a8e6] | 80, 443, 8080 | 13 |
| [2606:4700:24:ecc7:3c5e:d8bf:9242:a8e6] | 80, 443, 8080 | 13 |

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
