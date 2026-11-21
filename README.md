# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-21 18:21:05 +0330

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
| 104.19.27.249 | 80, 443, 8080 | 142 |
| 104.17.214.21 | 80, 443, 8080 | 142 |
| 104.17.23.142 | 80, 443, 8080 | 142 |
| 104.19.43.227 | 80, 443, 8080 | 142 |
| 104.18.116.175 | 80, 443, 8080 | 143 |
| 162.159.160.67 | 80, 443, 8080 | 156 |
| 162.159.160.67 | 80, 443, 8080 | 156 |
| 162.159.130.145 | 80, 443, 8080 | 166 |
| 162.159.153.161 | 80, 443, 8080 | 166 |
| 162.159.130.145 | 80, 443, 8080 | 166 |
| 162.159.153.161 | 80, 443, 8080 | 166 |
| 162.159.160.137 | 80, 443, 8080 | 183 |
| 162.159.160.137 | 80, 443, 8080 | 183 |
| 172.67.184.154 | 80, 443, 8080 | 191 |
| 172.67.184.154 | 80, 443, 8080 | 191 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3035:92a9:3d96:21c3:756f:f80e] | 80, 443, 8080 | 3 |
| [2606:4700:9c63:a82c:cef9:5772:bedd:dbe3] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:e191:287d:7a30:9c78:cec9] | 80, 443, 8080 | 3 |
| [2606:4700:3035:92a9:3d96:21c3:756f:f80e] | 80, 443, 8080 | 3 |
| [2606:4700:9c63:a82c:cef9:5772:bedd:dbe3] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:e191:287d:7a30:9c78:cec9] | 80, 443, 8080 | 3 |
| [2606:4700:3035:92a9:3d96:21c3:756f:f80e] | 80, 443, 8080 | 3 |
| [2606:4700:9c63:a82c:cef9:5772:bedd:dbe3] | 80, 443, 8080 | 3 |
| [2606:4700:8dee:e191:287d:7a30:9c78:cec9] | 80, 443, 8080 | 3 |
| [2606:4700:8de2:86a3:5255:3bcb:1918:4e1c] | 80, 443, 8080 | 4 |
| [2606:4700:8de2:86a3:5255:3bcb:1918:4e1c] | 80, 443, 8080 | 4 |
| [2606:4700:8de2:86a3:5255:3bcb:1918:4e1c] | 80, 443, 8080 | 4 |
| [2606:4700:3035:7bd:2035:fa3a:e7d5:4ba5] | 80, 443, 8080 | 14 |
| [2606:4700:3035:7bd:2035:fa3a:e7d5:4ba5] | 80, 443, 8080 | 14 |
| [2606:4700:3035:7bd:2035:fa3a:e7d5:4ba5] | 80, 443, 8080 | 14 |

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
