# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-28 17:49:42 +0330

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
| 198.41.209.62 | 80, 443, 8080 | 82 |
| 198.41.209.62 | 80, 443, 8080 | 82 |
| 198.41.209.194 | 80, 443, 8080 | 84 |
| 198.41.209.194 | 80, 443, 8080 | 84 |
| 198.41.211.73 | 80, 443, 8080 | 86 |
| 198.41.209.133 | 80, 443, 8080 | 97 |
| 198.41.209.133 | 80, 443, 8080 | 97 |
| 104.17.187.190 | 80, 443, 8080 | 150 |
| 104.17.84.158 | 80, 443, 8080 | 150 |
| 104.19.120.10 | 80, 443, 8080 | 152 |
| 198.41.209.36 | 80, 443, 8080 | 156 |
| 198.41.209.36 | 80, 443, 8080 | 156 |
| 162.159.160.181 | 80, 443, 8080 | 158 |
| 162.159.160.181 | 80, 443, 8080 | 158 |
| 104.17.100.49 | 80, 443, 8080 | 159 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b08:f4eb:b811:8367:c41e:3cf6] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:a69c:ee9d:3ebd:ccf6:ba50] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:ad2b:a9cd:b14d:a18d:4558] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:ba27:55f7:628c:853c:bbe9] | 80, 443, 8080 | 3 |
| [2606:4700:839c:10d2:3234:3cf1:6491:b282] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:f4eb:b811:8367:c41e:3cf6] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:a69c:ee9d:3ebd:ccf6:ba50] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:ad2b:a9cd:b14d:a18d:4558] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:ba27:55f7:628c:853c:bbe9] | 80, 443, 8080 | 3 |
| [2606:4700:839c:10d2:3234:3cf1:6491:b282] | 80, 443, 8080 | 3 |
| [2606:4700:9b08:f4eb:b811:8367:c41e:3cf6] | 80, 443, 8080 | 3 |
| [2606:4700:9b09:a69c:ee9d:3ebd:ccf6:ba50] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:ad2b:a9cd:b14d:a18d:4558] | 80, 443, 8080 | 3 |
| [2606:4700:8d9b:ba27:55f7:628c:853c:bbe9] | 80, 443, 8080 | 3 |
| [2606:4700:839c:10d2:3234:3cf1:6491:b282] | 80, 443, 8080 | 3 |

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
