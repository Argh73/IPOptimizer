# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-17 11:02:13 +0330

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
| 198.41.209.223 | 80, 443, 8080 | 67 |
| 198.41.209.223 | 80, 443, 8080 | 67 |
| 162.159.240.56 | 80, 443, 8080 | 141 |
| 104.18.131.11 | 80, 443, 8080 | 141 |
| 104.18.104.13 | 80, 443, 8080 | 141 |
| 104.17.244.215 | 80, 443, 8080 | 142 |
| 104.19.41.74 | 80, 443, 8080 | 142 |
| 172.67.122.216 | 80, 443, 8080 | 180 |
| 172.67.122.216 | 80, 443, 8080 | 180 |
| 162.159.195.77 | 80, 443, 8080 | 190 |
| 162.159.195.77 | 80, 443, 8080 | 190 |
| 172.67.158.86 | 80, 443, 8080 | 193 |
| 172.67.158.86 | 80, 443, 8080 | 193 |
| 172.64.82.47 | 80, 443, 8080 | 194 |
| 172.64.82.47 | 80, 443, 8080 | 194 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91bd:a176:c205:6ace:b49:e2fc] | 80, 443, 8080 | 0 |
| [2606:4700:91bd:a176:c205:6ace:b49:e2fc] | 80, 443, 8080 | 0 |
| [2606:4700:91bd:a176:c205:6ace:b49:e2fc] | 80, 443, 8080 | 0 |
| [2606:4700:90d3:b048:8e14:48f5:9db4:d01c] | 80, 443, 8080 | 1 |
| [2606:4700:9c62:d5b2:8148:320f:8e80:85d6] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:28eb:2d96:45e5:3ac2:36d3] | 80, 443, 8080 | 1 |
| [2606:4700:839f:33ae:e62e:1359:b68d:5c6c] | 80, 443, 8080 | 1 |
| [2606:4700:90d3:b048:8e14:48f5:9db4:d01c] | 80, 443, 8080 | 1 |
| [2606:4700:9c62:d5b2:8148:320f:8e80:85d6] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:28eb:2d96:45e5:3ac2:36d3] | 80, 443, 8080 | 1 |
| [2606:4700:839f:33ae:e62e:1359:b68d:5c6c] | 80, 443, 8080 | 1 |
| [2606:4700:90d3:b048:8e14:48f5:9db4:d01c] | 80, 443, 8080 | 1 |
| [2606:4700:9c62:d5b2:8148:320f:8e80:85d6] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:28eb:2d96:45e5:3ac2:36d3] | 80, 443, 8080 | 1 |
| [2606:4700:839f:33ae:e62e:1359:b68d:5c6c] | 80, 443, 8080 | 1 |

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
