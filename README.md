# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-10 15:10:56 +0330

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
| 198.41.208.175 | 80, 443, 8080 | 48 |
| 198.41.208.175 | 80, 443, 8080 | 48 |
| 198.41.209.183 | 80, 443, 8080 | 49 |
| 198.41.208.253 | 80, 443, 8080 | 49 |
| 198.41.209.183 | 80, 443, 8080 | 49 |
| 198.41.208.253 | 80, 443, 8080 | 49 |
| 198.41.209.120 | 80, 443, 8080 | 52 |
| 198.41.209.120 | 80, 443, 8080 | 52 |
| 198.41.209.49 | 80, 443, 8080 | 53 |
| 198.41.209.49 | 80, 443, 8080 | 53 |
| 198.41.211.137 | 80, 443, 8080 | 70 |
| 198.41.223.140 | 80, 443, 8080 | 79 |
| 104.19.140.11 | 80, 443, 8080 | 138 |
| 104.16.158.207 | 80, 443, 8080 | 141 |
| 104.16.77.201 | 80, 443, 8080 | 142 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91b6:c450:8975:4b1b:6688:4dc1] | 80, 443, 8080 | 3 |
| [2606:4700:9b01:c4e2:ab62:b57b:e9e5:d63f] | 80, 443, 8080 | 3 |
| [2606:4700:4405:69ae:696f:71ec:e038:2513] | 80, 443, 8080 | 3 |
| [2606:4700:8ded:a92f:a302:95c5:b9af:f532] | 80, 443, 8080 | 3 |
| [2606:4700:91b6:c450:8975:4b1b:6688:4dc1] | 80, 443, 8080 | 3 |
| [2606:4700:9b01:c4e2:ab62:b57b:e9e5:d63f] | 80, 443, 8080 | 3 |
| [2606:4700:4405:69ae:696f:71ec:e038:2513] | 80, 443, 8080 | 3 |
| [2606:4700:8ded:a92f:a302:95c5:b9af:f532] | 80, 443, 8080 | 3 |
| [2606:4700:91b6:c450:8975:4b1b:6688:4dc1] | 80, 443, 8080 | 3 |
| [2606:4700:9b01:c4e2:ab62:b57b:e9e5:d63f] | 80, 443, 8080 | 3 |
| [2606:4700:4405:69ae:696f:71ec:e038:2513] | 80, 443, 8080 | 3 |
| [2606:4700:8ded:a92f:a302:95c5:b9af:f532] | 80, 443, 8080 | 3 |
| [2606:4700:9c6d:10c1:fb31:3672:b239:3112] | 80, 443, 8080 | 4 |
| [2606:4700:9c6d:10c1:fb31:3672:b239:3112] | 80, 443, 8080 | 4 |
| [2606:4700:9c6d:10c1:fb31:3672:b239:3112] | 80, 443, 8080 | 4 |

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
