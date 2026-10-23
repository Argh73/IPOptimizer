# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-24 02:48:22 +0330

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
| 198.41.209.88 | 80, 443, 8080 | 50 |
| 198.41.209.63 | 80, 443, 8080 | 50 |
| 198.41.208.34 | 80, 443, 8080 | 54 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.209.146 | 80, 443, 8080 | 59 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.18.233.197 | 80, 443, 8080 | 151 |
| 104.18.86.164 | 80, 443, 8080 | 151 |
| 162.159.193.54 | 80, 443, 8080 | 151 |
| 104.18.245.67 | 80, 443, 8080 | 151 |
| 104.16.24.39 | 80, 443, 8080 | 151 |
| 162.159.129.55 | 80, 443, 8080 | 161 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c68:9d7f:a89:347b:4013:9108] | 80, 443, 8080 | 3 |
| [2606:4700:9c68:3b97:8416:7cd7:f4f2:2ec3] | 80, 443, 8080 | 3 |
| [2606:4700:9b07:c6ec:c373:93aa:afdd:6af2] | 80, 443, 8080 | 3 |
| [2606:4700:9b07:4b14:7540:b4f3:b9d4:86be] | 80, 443, 8080 | 3 |
| [2606:4700:9c68:9d7f:a89:347b:4013:9108] | 80, 443, 8080 | 3 |
| [2606:4700:9c68:3b97:8416:7cd7:f4f2:2ec3] | 80, 443, 8080 | 3 |
| [2606:4700:9b07:c6ec:c373:93aa:afdd:6af2] | 80, 443, 8080 | 3 |
| [2606:4700:9b07:4b14:7540:b4f3:b9d4:86be] | 80, 443, 8080 | 3 |
| [2606:4700:9c68:9d7f:a89:347b:4013:9108] | 80, 443, 8080 | 3 |
| [2606:4700:9c68:3b97:8416:7cd7:f4f2:2ec3] | 80, 443, 8080 | 3 |
| [2606:4700:9b07:c6ec:c373:93aa:afdd:6af2] | 80, 443, 8080 | 3 |
| [2606:4700:9b07:4b14:7540:b4f3:b9d4:86be] | 80, 443, 8080 | 3 |
| [2606:4700:83b6:2601:68bb:9ffc:acc9:b4b1] | 80, 443, 8080 | 167 |
| [2606:4700:83b6:2601:68bb:9ffc:acc9:b4b1] | 80, 443, 8080 | 167 |
| [2606:4700:83b6:2601:68bb:9ffc:acc9:b4b1] | 80, 443, 8080 | 167 |

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
