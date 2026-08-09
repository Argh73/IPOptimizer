# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-10 00:31:41 +0330

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
| 198.41.209.234 | 80, 443, 8080 | 53 |
| 198.41.209.234 | 80, 443, 8080 | 53 |
| 198.41.208.58 | 80, 443, 8080 | 61 |
| 198.41.208.58 | 80, 443, 8080 | 61 |
| 198.41.208.141 | 80, 443, 8080 | 86 |
| 198.41.208.141 | 80, 443, 8080 | 86 |
| 104.19.142.93 | 80, 443, 8080 | 138 |
| 104.19.90.107 | 80, 443, 8080 | 139 |
| 104.16.222.15 | 80, 443, 8080 | 139 |
| 104.19.248.5 | 80, 443, 8080 | 139 |
| 104.16.3.45 | 80, 443, 8080 | 139 |
| 172.67.108.84 | 80, 443, 8080 | 183 |
| 172.67.108.84 | 80, 443, 8080 | 183 |
| 173.245.49.83 | 80, 443, 8080 | 184 |
| 173.245.49.83 | 80, 443, 8080 | 184 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c63:8a6f:b427:f150:e4eb:a76f] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:81ef:3ca3:c061:7d72:4203] | 80, 443, 8080 | 1 |
| [2606:4700:9769:d9dc:f0f5:f1ce:1597:95c8] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:8a6f:b427:f150:e4eb:a76f] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:81ef:3ca3:c061:7d72:4203] | 80, 443, 8080 | 1 |
| [2606:4700:9769:d9dc:f0f5:f1ce:1597:95c8] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:8a6f:b427:f150:e4eb:a76f] | 80, 443, 8080 | 1 |
| [2606:4700:9c63:81ef:3ca3:c061:7d72:4203] | 80, 443, 8080 | 1 |
| [2606:4700:9769:d9dc:f0f5:f1ce:1597:95c8] | 80, 443, 8080 | 1 |
| [2606:4700:8ca5:a0c3:500e:8d2b:6ac:bfe9] | 80, 443, 8080 | 133 |
| [2606:4700:8ca5:a0c3:500e:8d2b:6ac:bfe9] | 80, 443, 8080 | 133 |
| [2606:4700:8ca5:a0c3:500e:8d2b:6ac:bfe9] | 80, 443, 8080 | 133 |
| [2606:4700:8ca5:7f6d:b635:119:4fcb:77e6] | 80, 443, 8080 | 135 |
| [2606:4700:8ca5:7f6d:b635:119:4fcb:77e6] | 80, 443, 8080 | 135 |
| [2606:4700:8ca5:7f6d:b635:119:4fcb:77e6] | 80, 443, 8080 | 135 |

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
