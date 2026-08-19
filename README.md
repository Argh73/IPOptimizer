# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-20 00:23:27 +0330

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
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 198.41.209.104 | 80, 443, 8080 | 136 |
| 104.19.13.167 | 80, 443, 8080 | 138 |
| 104.19.165.50 | 80, 443, 8080 | 139 |
| 104.17.99.36 | 80, 443, 8080 | 139 |
| 104.18.182.160 | 80, 443, 8080 | 139 |
| 104.17.93.68 | 80, 443, 8080 | 139 |
| 198.41.209.1 | 80, 443, 8080 | 167 |
| 198.41.209.1 | 80, 443, 8080 | 167 |
| 172.67.167.165 | 80, 443, 8080 | 190 |
| 172.67.167.165 | 80, 443, 8080 | 190 |
| 162.159.160.152 | 80, 443, 8080 | 192 |
| 162.159.160.152 | 80, 443, 8080 | 192 |
| 172.67.121.50 | 80, 443, 8080 | 201 |
| 172.67.121.50 | 80, 443, 8080 | 201 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3009:2e03:4124:66bf:5303:1c22] | 80, 443, 8080 | 0 |
| [2606:4700:3009:4c85:8480:128b:3408:14e4] | 80, 443, 8080 | 0 |
| [2606:4700:3009:2e03:4124:66bf:5303:1c22] | 80, 443, 8080 | 0 |
| [2606:4700:3009:4c85:8480:128b:3408:14e4] | 80, 443, 8080 | 0 |
| [2606:4700:3009:2e03:4124:66bf:5303:1c22] | 80, 443, 8080 | 0 |
| [2606:4700:3009:4c85:8480:128b:3408:14e4] | 80, 443, 8080 | 0 |
| [2606:4700:8d7f:6d8d:c38e:3f7d:2b32:d29d] | 80, 443, 8080 | 1 |
| [2606:4700:8de1:d782:cc35:c34c:f4e:3d2b] | 80, 443, 8080 | 1 |
| [2606:4700:8de1:4d73:dd37:3a87:1a53:eb01] | 80, 443, 8080 | 1 |
| [2606:4700:8d7f:6d8d:c38e:3f7d:2b32:d29d] | 80, 443, 8080 | 1 |
| [2606:4700:8de1:d782:cc35:c34c:f4e:3d2b] | 80, 443, 8080 | 1 |
| [2606:4700:8de1:4d73:dd37:3a87:1a53:eb01] | 80, 443, 8080 | 1 |
| [2606:4700:8d7f:6d8d:c38e:3f7d:2b32:d29d] | 80, 443, 8080 | 1 |
| [2606:4700:8de1:d782:cc35:c34c:f4e:3d2b] | 80, 443, 8080 | 1 |
| [2606:4700:8de1:4d73:dd37:3a87:1a53:eb01] | 80, 443, 8080 | 1 |

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
