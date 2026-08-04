# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-04 12:50:32 +0330

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
| 198.41.208.22 | 80, 443, 8080 | 51 |
| 198.41.208.22 | 80, 443, 8080 | 51 |
| 198.41.208.148 | 80, 443, 8080 | 54 |
| 198.41.208.148 | 80, 443, 8080 | 54 |
| 198.41.209.58 | 80, 443, 8080 | 55 |
| 198.41.209.58 | 80, 443, 8080 | 55 |
| 198.41.208.31 | 80, 443, 8080 | 58 |
| 198.41.208.31 | 80, 443, 8080 | 58 |
| 198.41.222.9 | 80, 443, 8080 | 65 |
| 198.41.211.48 | 80, 443, 8080 | 100 |
| 104.16.157.158 | 80, 443, 8080 | 142 |
| 172.67.243.64 | 80, 443, 8080 | 154 |
| 104.16.102.33 | 80, 443, 8080 | 155 |
| 198.41.209.68 | 80, 443, 8080 | 169 |
| 198.41.209.68 | 80, 443, 8080 | 169 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ad8:78b0:71b7:193f:8ed:d5cd] | 80, 443, 8080 | 0 |
| [2606:4700:9a67:71ce:e2f7:19bf:ff71:d522] | 80, 443, 8080 | 0 |
| [2606:4700:91bd:a1b0:88cb:9c8d:f155:556] | 80, 443, 8080 | 0 |
| [2606:4700:9ad9:4d73:fa85:de5d:f7ee:b3f6] | 80, 443, 8080 | 0 |
| [2606:4700:9ad8:78b0:71b7:193f:8ed:d5cd] | 80, 443, 8080 | 0 |
| [2606:4700:9a67:71ce:e2f7:19bf:ff71:d522] | 80, 443, 8080 | 0 |
| [2606:4700:91bd:a1b0:88cb:9c8d:f155:556] | 80, 443, 8080 | 0 |
| [2606:4700:9ad9:4d73:fa85:de5d:f7ee:b3f6] | 80, 443, 8080 | 0 |
| [2606:4700:9ad8:78b0:71b7:193f:8ed:d5cd] | 80, 443, 8080 | 0 |
| [2606:4700:9a67:71ce:e2f7:19bf:ff71:d522] | 80, 443, 8080 | 0 |
| [2606:4700:91bd:a1b0:88cb:9c8d:f155:556] | 80, 443, 8080 | 0 |
| [2606:4700:9ad9:4d73:fa85:de5d:f7ee:b3f6] | 80, 443, 8080 | 0 |
| [2606:4700:9ad9:9335:ed9c:f5a8:1ce0:7c0c] | 80, 443, 8080 | 1 |
| [2606:4700:9ad9:9335:ed9c:f5a8:1ce0:7c0c] | 80, 443, 8080 | 1 |
| [2606:4700:9ad9:9335:ed9c:f5a8:1ce0:7c0c] | 80, 443, 8080 | 1 |

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
