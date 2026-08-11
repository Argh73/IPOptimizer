# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-11 11:15:26 +0330

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
| 198.41.208.165 | 80, 443, 8080 | 56 |
| 198.41.208.165 | 80, 443, 8080 | 56 |
| 198.41.208.173 | 80, 443, 8080 | 57 |
| 198.41.208.173 | 80, 443, 8080 | 57 |
| 198.41.209.170 | 80, 443, 8080 | 72 |
| 198.41.209.170 | 80, 443, 8080 | 72 |
| 162.159.46.47 | 80, 443, 8080 | 75 |
| 104.16.248.212 | 80, 443, 8080 | 142 |
| 104.17.70.42 | 80, 443, 8080 | 142 |
| 104.16.109.151 | 80, 443, 8080 | 142 |
| 104.17.112.85 | 80, 443, 8080 | 142 |
| 198.41.209.205 | 80, 443, 8080 | 162 |
| 198.41.209.205 | 80, 443, 8080 | 162 |
| 198.41.208.241 | 80, 443, 8080 | 179 |
| 198.41.208.241 | 80, 443, 8080 | 179 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91b0:7c71:6ca2:6437:f8b2:4d1e] | 80, 443, 8080 | 3 |
| [2606:4700:2c:df76:cdce:4f4b:d6b7:35ac] | 80, 443, 8080 | 3 |
| [2606:4700:99e5:b20e:fc49:bef3:9d1e:1faf] | 80, 443, 8080 | 3 |
| [2606:4700:9a90:ff98:dadd:f6a5:2bc1:11e] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:7c71:6ca2:6437:f8b2:4d1e] | 80, 443, 8080 | 3 |
| [2606:4700:2c:df76:cdce:4f4b:d6b7:35ac] | 80, 443, 8080 | 3 |
| [2606:4700:99e5:b20e:fc49:bef3:9d1e:1faf] | 80, 443, 8080 | 3 |
| [2606:4700:9a90:ff98:dadd:f6a5:2bc1:11e] | 80, 443, 8080 | 3 |
| [2606:4700:91b0:7c71:6ca2:6437:f8b2:4d1e] | 80, 443, 8080 | 3 |
| [2606:4700:2c:df76:cdce:4f4b:d6b7:35ac] | 80, 443, 8080 | 3 |
| [2606:4700:99e5:b20e:fc49:bef3:9d1e:1faf] | 80, 443, 8080 | 3 |
| [2606:4700:9a90:ff98:dadd:f6a5:2bc1:11e] | 80, 443, 8080 | 3 |
| [2606:4700:2c:3cfe:5adf:70de:cb54:b508] | 80, 443, 8080 | 12 |
| [2606:4700:2c:3cfe:5adf:70de:cb54:b508] | 80, 443, 8080 | 12 |
| [2606:4700:2c:3cfe:5adf:70de:cb54:b508] | 80, 443, 8080 | 12 |

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
