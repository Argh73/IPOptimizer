# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-02 00:54:15 +0330

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
| 198.41.209.132 | 80, 443, 8080 | 51 |
| 198.41.209.132 | 80, 443, 8080 | 51 |
| 198.41.208.203 | 80, 443, 8080 | 52 |
| 198.41.208.203 | 80, 443, 8080 | 52 |
| 198.41.209.140 | 80, 443, 8080 | 54 |
| 198.41.209.89 | 80, 443, 8080 | 54 |
| 198.41.209.140 | 80, 443, 8080 | 54 |
| 198.41.209.89 | 80, 443, 8080 | 54 |
| 198.41.208.16 | 80, 443, 8080 | 56 |
| 198.41.208.16 | 80, 443, 8080 | 56 |
| 104.19.80.23 | 80, 443, 8080 | 139 |
| 104.16.146.180 | 80, 443, 8080 | 140 |
| 104.19.215.101 | 80, 443, 8080 | 140 |
| 104.16.83.88 | 80, 443, 8080 | 140 |
| 104.21.212.195 | 80, 443, 8080 | 154 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:964e:1398:346a:cdcc:1e81:121e] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:2f79:69db:c202:85be:e2c3] | 80, 443, 8080 | 3 |
| [2606:4700:964e:1398:346a:cdcc:1e81:121e] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:2f79:69db:c202:85be:e2c3] | 80, 443, 8080 | 3 |
| [2606:4700:964e:1398:346a:cdcc:1e81:121e] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:2f79:69db:c202:85be:e2c3] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:b4db:f480:7611:f44a:a790] | 80, 443, 8080 | 4 |
| [2606:4700:9ae9:b4db:f480:7611:f44a:a790] | 80, 443, 8080 | 4 |
| [2606:4700:9ae9:b4db:f480:7611:f44a:a790] | 80, 443, 8080 | 4 |
| [2606:4700:17:7892:8b8a:43dc:6cd0:b528] | 80, 443, 8080 | 5 |
| [2606:4700:17:7892:8b8a:43dc:6cd0:b528] | 80, 443, 8080 | 5 |
| [2606:4700:17:7892:8b8a:43dc:6cd0:b528] | 80, 443, 8080 | 5 |
| [2606:4700:17:5961:599a:c7a7:44ea:a895] | 80, 443, 8080 | 13 |
| [2606:4700:17:5961:599a:c7a7:44ea:a895] | 80, 443, 8080 | 13 |
| [2606:4700:17:5961:599a:c7a7:44ea:a895] | 80, 443, 8080 | 13 |

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
