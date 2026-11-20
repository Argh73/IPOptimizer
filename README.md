# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-20 19:10:41 +0330

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
| 104.17.93.11 | 80, 443, 8080 | 142 |
| 162.159.244.203 | 80, 443, 8080 | 142 |
| 104.19.106.156 | 80, 443, 8080 | 142 |
| 104.19.223.99 | 80, 443, 8080 | 143 |
| 104.19.61.70 | 80, 443, 8080 | 143 |
| 162.159.160.179 | 80, 443, 8080 | 146 |
| 162.159.160.179 | 80, 443, 8080 | 146 |
| 162.159.160.16 | 80, 443, 8080 | 155 |
| 162.159.160.16 | 80, 443, 8080 | 155 |
| 162.159.160.30 | 80, 443, 8080 | 162 |
| 162.159.160.30 | 80, 443, 8080 | 162 |
| 162.159.133.238 | 80, 443, 8080 | 166 |
| 162.159.133.238 | 80, 443, 8080 | 166 |
| 162.159.129.248 | 80, 443, 8080 | 167 |
| 162.159.129.248 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8de1:5c6:57fe:660:5ba:df94] | 80, 443, 8080 | 3 |
| [2606:4700:137:8a54:ddab:a8e:9e2c:3a65] | 80, 443, 8080 | 3 |
| [2606:4700:8de1:5c6:57fe:660:5ba:df94] | 80, 443, 8080 | 3 |
| [2606:4700:137:8a54:ddab:a8e:9e2c:3a65] | 80, 443, 8080 | 3 |
| [2606:4700:8de1:5c6:57fe:660:5ba:df94] | 80, 443, 8080 | 3 |
| [2606:4700:137:8a54:ddab:a8e:9e2c:3a65] | 80, 443, 8080 | 3 |
| [2606:4700:91b8:126a:3e1c:bb4f:291e:cfd8] | 80, 443, 8080 | 5 |
| [2606:4700:91b8:126a:3e1c:bb4f:291e:cfd8] | 80, 443, 8080 | 5 |
| [2606:4700:91b8:126a:3e1c:bb4f:291e:cfd8] | 80, 443, 8080 | 5 |
| [2606:4700:8ca8:ae4c:233:b570:94a1:3b54] | 80, 443, 8080 | 125 |
| [2606:4700:8ca8:ae4c:233:b570:94a1:3b54] | 80, 443, 8080 | 125 |
| [2606:4700:8ca8:ae4c:233:b570:94a1:3b54] | 80, 443, 8080 | 125 |
| [2606:4700:8ca8:e57:4da1:1e9b:de68:9fa4] | 80, 443, 8080 | 144 |
| [2606:4700:8ca8:e57:4da1:1e9b:de68:9fa4] | 80, 443, 8080 | 144 |
| [2606:4700:8ca8:e57:4da1:1e9b:de68:9fa4] | 80, 443, 8080 | 144 |

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
