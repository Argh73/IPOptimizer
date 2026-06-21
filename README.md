# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-21 13:40:00 +0330

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
| 198.41.223.108 | 80, 443, 8080 | 71 |
| 198.41.223.108 | 80, 443, 8080 | 71 |
| 198.41.223.108 | 80, 443, 8080 | 71 |
| 104.17.243.225 | 80, 443, 8080 | 133 |
| 104.18.180.0 | 80, 443, 8080 | 133 |
| 104.18.209.25 | 80, 443, 8080 | 133 |
| 104.18.103.237 | 80, 443, 8080 | 133 |
| 104.17.243.225 | 80, 443, 8080 | 133 |
| 104.18.180.0 | 80, 443, 8080 | 133 |
| 104.18.209.25 | 80, 443, 8080 | 133 |
| 104.18.103.237 | 80, 443, 8080 | 133 |
| 104.17.243.225 | 80, 443, 8080 | 133 |
| 104.18.180.0 | 80, 443, 8080 | 133 |
| 104.18.209.25 | 80, 443, 8080 | 133 |
| 104.18.103.237 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d77:f232:35d6:b3a4:c9ab:f0c6] | 80, 443, 8080 | 3 |
| [2606:4700:9a64:dc46:474a:2c7e:fb2c:2404] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:50c1:64d6:50e7:d68:94d6] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:f232:35d6:b3a4:c9ab:f0c6] | 80, 443, 8080 | 3 |
| [2606:4700:9a64:dc46:474a:2c7e:fb2c:2404] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:50c1:64d6:50e7:d68:94d6] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:f232:35d6:b3a4:c9ab:f0c6] | 80, 443, 8080 | 3 |
| [2606:4700:9a64:dc46:474a:2c7e:fb2c:2404] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:50c1:64d6:50e7:d68:94d6] | 80, 443, 8080 | 3 |
| [2606:4700:4400:5e5e:8d5f:1bfc:59f9:e3dd] | 80, 443, 8080 | 13 |
| [2606:4700:4406:ca74:ac46:e766:8c72:24f4] | 80, 443, 8080 | 13 |
| [2606:4700:4400:5e5e:8d5f:1bfc:59f9:e3dd] | 80, 443, 8080 | 13 |
| [2606:4700:4406:ca74:ac46:e766:8c72:24f4] | 80, 443, 8080 | 13 |
| [2606:4700:4400:5e5e:8d5f:1bfc:59f9:e3dd] | 80, 443, 8080 | 13 |
| [2606:4700:4406:ca74:ac46:e766:8c72:24f4] | 80, 443, 8080 | 13 |

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
