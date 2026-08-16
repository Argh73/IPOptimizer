# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-16 10:38:56 +0330

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
| 198.41.209.119 | 80, 443, 8080 | 116 |
| 198.41.209.119 | 80, 443, 8080 | 116 |
| 198.41.208.159 | 80, 443, 8080 | 133 |
| 198.41.208.159 | 80, 443, 8080 | 133 |
| 104.18.140.205 | 80, 443, 8080 | 141 |
| 104.18.206.212 | 80, 443, 8080 | 141 |
| 104.16.231.250 | 80, 443, 8080 | 141 |
| 104.21.227.47 | 80, 443, 8080 | 142 |
| 104.18.117.163 | 80, 443, 8080 | 142 |
| 198.41.209.101 | 80, 443, 8080 | 158 |
| 198.41.209.101 | 80, 443, 8080 | 158 |
| 141.101.113.88 | 80, 443, 8080 | 184 |
| 141.101.113.88 | 80, 443, 8080 | 184 |
| 162.159.46.46 | 80, 443, 8080 | 195 |
| 162.159.46.46 | 80, 443, 8080 | 195 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de4:9237:50f8:ff6a:a44a:4559] | 80, 443, 8080 | 11 |
| [2606:4700:8de4:9237:50f8:ff6a:a44a:4559] | 80, 443, 8080 | 11 |
| [2606:4700:8de4:9237:50f8:ff6a:a44a:4559] | 80, 443, 8080 | 11 |
| [2606:4700:8caf:4566:f5fb:fd5b:2f4d:601c] | 80, 443, 8080 | 12 |
| [2606:4700:8caf:9ac:6c15:94b2:8e39:6976] | 80, 443, 8080 | 12 |
| [2606:4700:8caf:4566:f5fb:fd5b:2f4d:601c] | 80, 443, 8080 | 12 |
| [2606:4700:8caf:9ac:6c15:94b2:8e39:6976] | 80, 443, 8080 | 12 |
| [2606:4700:8caf:4566:f5fb:fd5b:2f4d:601c] | 80, 443, 8080 | 12 |
| [2606:4700:8caf:9ac:6c15:94b2:8e39:6976] | 80, 443, 8080 | 12 |
| [2606:4700:91b5:6cb2:fbc7:5a97:7f2:72c2] | 80, 443, 8080 | 22 |
| [2606:4700:91b5:6cb2:fbc7:5a97:7f2:72c2] | 80, 443, 8080 | 22 |
| [2606:4700:91b5:6cb2:fbc7:5a97:7f2:72c2] | 80, 443, 8080 | 22 |
| [2606:4700:310c:591f:5ea5:571f:5b5d:2511] | 80, 443, 8080 | 26 |
| [2606:4700:310c:591f:5ea5:571f:5b5d:2511] | 80, 443, 8080 | 26 |
| [2606:4700:310c:591f:5ea5:571f:5b5d:2511] | 80, 443, 8080 | 26 |

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
