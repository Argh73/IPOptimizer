# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-23 10:40:27 +0330

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
| 198.41.208.59 | 80, 443, 8080 | 46 |
| 198.41.208.59 | 80, 443, 8080 | 46 |
| 198.41.209.0 | 80, 443, 8080 | 47 |
| 198.41.209.138 | 80, 443, 8080 | 47 |
| 198.41.209.193 | 80, 443, 8080 | 47 |
| 198.41.209.0 | 80, 443, 8080 | 47 |
| 198.41.209.138 | 80, 443, 8080 | 47 |
| 198.41.209.193 | 80, 443, 8080 | 47 |
| 198.41.208.86 | 80, 443, 8080 | 48 |
| 198.41.208.86 | 80, 443, 8080 | 48 |
| 104.16.88.178 | 80, 443, 8080 | 141 |
| 104.17.128.125 | 80, 443, 8080 | 141 |
| 104.16.9.201 | 80, 443, 8080 | 142 |
| 104.18.63.244 | 80, 443, 8080 | 150 |
| 104.17.228.21 | 80, 443, 8080 | 151 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:29:2252:8871:7122:42c8:47e3] | 80, 443, 8080 | 0 |
| [2606:4700:4700:91f3:b96e:b47a:6cd6:3273] | 80, 443, 8080 | 0 |
| [2606:4700:29:2252:8871:7122:42c8:47e3] | 80, 443, 8080 | 0 |
| [2606:4700:4700:91f3:b96e:b47a:6cd6:3273] | 80, 443, 8080 | 0 |
| [2606:4700:29:2252:8871:7122:42c8:47e3] | 80, 443, 8080 | 0 |
| [2606:4700:4700:91f3:b96e:b47a:6cd6:3273] | 80, 443, 8080 | 0 |
| [2606:4700:29:2b0b:4453:f715:a959:2397] | 80, 443, 8080 | 1 |
| [2606:4700:9b05:ddd0:a867:d54b:25b5:4f9c] | 80, 443, 8080 | 1 |
| [2606:4700:4700:27d1:814e:c31:225e:56e2] | 80, 443, 8080 | 1 |
| [2606:4700:29:2b0b:4453:f715:a959:2397] | 80, 443, 8080 | 1 |
| [2606:4700:9b05:ddd0:a867:d54b:25b5:4f9c] | 80, 443, 8080 | 1 |
| [2606:4700:4700:27d1:814e:c31:225e:56e2] | 80, 443, 8080 | 1 |
| [2606:4700:29:2b0b:4453:f715:a959:2397] | 80, 443, 8080 | 1 |
| [2606:4700:9b05:ddd0:a867:d54b:25b5:4f9c] | 80, 443, 8080 | 1 |
| [2606:4700:4700:27d1:814e:c31:225e:56e2] | 80, 443, 8080 | 1 |

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
