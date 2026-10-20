# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-21 02:46:54 +0330

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
| 198.41.209.156 | 80, 443, 8080 | 48 |
| 198.41.208.201 | 80, 443, 8080 | 48 |
| 198.41.209.156 | 80, 443, 8080 | 48 |
| 198.41.208.201 | 80, 443, 8080 | 48 |
| 198.41.209.222 | 80, 443, 8080 | 49 |
| 198.41.208.228 | 80, 443, 8080 | 49 |
| 198.41.209.222 | 80, 443, 8080 | 49 |
| 198.41.208.228 | 80, 443, 8080 | 49 |
| 198.41.209.119 | 80, 443, 8080 | 51 |
| 198.41.209.119 | 80, 443, 8080 | 51 |
| 104.17.103.64 | 80, 443, 8080 | 137 |
| 104.16.198.1 | 80, 443, 8080 | 138 |
| 104.16.239.95 | 80, 443, 8080 | 138 |
| 104.19.209.100 | 80, 443, 8080 | 138 |
| 104.16.188.149 | 80, 443, 8080 | 138 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9763:47e3:5170:b2a7:fc94:355f] | 80, 443, 8080 | 3 |
| [2606:4700:8de6:aace:72a1:3294:902f:5008] | 80, 443, 8080 | 3 |
| [2606:4700:9763:ec82:4b21:29cf:c53e:9770] | 80, 443, 8080 | 3 |
| [2606:4700:9763:47e3:5170:b2a7:fc94:355f] | 80, 443, 8080 | 3 |
| [2606:4700:8de6:aace:72a1:3294:902f:5008] | 80, 443, 8080 | 3 |
| [2606:4700:9763:ec82:4b21:29cf:c53e:9770] | 80, 443, 8080 | 3 |
| [2606:4700:9763:47e3:5170:b2a7:fc94:355f] | 80, 443, 8080 | 3 |
| [2606:4700:8de6:aace:72a1:3294:902f:5008] | 80, 443, 8080 | 3 |
| [2606:4700:9763:ec82:4b21:29cf:c53e:9770] | 80, 443, 8080 | 3 |
| [2606:4700:8ca5:5b10:62c8:d64:6a61:5a64] | 80, 443, 8080 | 126 |
| [2606:4700:8ca5:5b10:62c8:d64:6a61:5a64] | 80, 443, 8080 | 126 |
| [2606:4700:8ca5:5b10:62c8:d64:6a61:5a64] | 80, 443, 8080 | 126 |
| [2606:4700:8ca5:547:8e86:bb16:573e:99aa] | 80, 443, 8080 | 140 |
| [2606:4700:8ca5:547:8e86:bb16:573e:99aa] | 80, 443, 8080 | 140 |
| [2606:4700:8ca5:547:8e86:bb16:573e:99aa] | 80, 443, 8080 | 140 |

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
