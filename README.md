# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-08 10:59:00 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.208.162 | 80, 443, 8080 | 60 |
| 198.41.208.162 | 80, 443, 8080 | 60 |
| 162.159.46.149 | 80, 443, 8080 | 85 |
| 104.17.212.116 | 80, 443, 8080 | 142 |
| 104.18.149.150 | 80, 443, 8080 | 142 |
| 104.19.53.143 | 80, 443, 8080 | 142 |
| 104.16.73.79 | 80, 443, 8080 | 143 |
| 198.41.208.160 | 80, 443, 8080 | 164 |
| 198.41.208.160 | 80, 443, 8080 | 164 |
| 172.67.169.194 | 80, 443, 8080 | 192 |
| 172.67.169.194 | 80, 443, 8080 | 192 |
| 172.64.84.205 | 80, 443, 8080 | 197 |
| 172.64.84.205 | 80, 443, 8080 | 197 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a66:cfe7:b448:9f66:5ac0:ae0c] | 80, 443, 8080 | 3 |
| [2606:4700:137:710e:f198:3407:ea1e:1b50] | 80, 443, 8080 | 3 |
| [2606:4700:9a66:20e3:8a7f:44ca:bf6d:a41c] | 80, 443, 8080 | 3 |
| [2606:4700:17:3d52:72d0:3851:37b6:1b55] | 80, 443, 8080 | 3 |
| [2606:4700:976d:8d25:79b7:6efc:acbb:7357] | 80, 443, 8080 | 3 |
| [2606:4700:9a66:cfe7:b448:9f66:5ac0:ae0c] | 80, 443, 8080 | 3 |
| [2606:4700:137:710e:f198:3407:ea1e:1b50] | 80, 443, 8080 | 3 |
| [2606:4700:9a66:20e3:8a7f:44ca:bf6d:a41c] | 80, 443, 8080 | 3 |
| [2606:4700:17:3d52:72d0:3851:37b6:1b55] | 80, 443, 8080 | 3 |
| [2606:4700:976d:8d25:79b7:6efc:acbb:7357] | 80, 443, 8080 | 3 |
| [2606:4700:9a66:cfe7:b448:9f66:5ac0:ae0c] | 80, 443, 8080 | 3 |
| [2606:4700:137:710e:f198:3407:ea1e:1b50] | 80, 443, 8080 | 3 |
| [2606:4700:9a66:20e3:8a7f:44ca:bf6d:a41c] | 80, 443, 8080 | 3 |
| [2606:4700:17:3d52:72d0:3851:37b6:1b55] | 80, 443, 8080 | 3 |
| [2606:4700:976d:8d25:79b7:6efc:acbb:7357] | 80, 443, 8080 | 3 |

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
