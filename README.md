# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-17 02:26:46 +0330

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
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 172.67.152.13 | 80, 443, 8080 | 93 |
| 172.67.151.5 | 80, 443, 8080 | 93 |
| 172.67.154.35 | 80, 443, 8080 | 94 |
| 172.67.151.120 | 80, 443, 8080 | 94 |
| 172.67.149.53 | 80, 443, 8080 | 95 |
| 104.16.133.125 | 80, 443, 8080 | 138 |
| 104.16.94.22 | 80, 443, 8080 | 138 |
| 104.19.83.166 | 80, 443, 8080 | 138 |
| 104.19.160.99 | 80, 443, 8080 | 138 |
| 104.19.252.156 | 80, 443, 8080 | 138 |
| 172.67.251.117 | 80, 443, 8080 | 145 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:976e:4083:8289:4b63:f4f0:fccf] | 80, 443, 8080 | 3 |
| [2606:4700:440f:6c34:fa66:214d:259c:be01] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:b855:4620:cd34:10bf:d7cf] | 80, 443, 8080 | 3 |
| [2606:4700:976e:4083:8289:4b63:f4f0:fccf] | 80, 443, 8080 | 3 |
| [2606:4700:440f:6c34:fa66:214d:259c:be01] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:b855:4620:cd34:10bf:d7cf] | 80, 443, 8080 | 3 |
| [2606:4700:976e:4083:8289:4b63:f4f0:fccf] | 80, 443, 8080 | 3 |
| [2606:4700:440f:6c34:fa66:214d:259c:be01] | 80, 443, 8080 | 3 |
| [2606:4700:9b0f:b855:4620:cd34:10bf:d7cf] | 80, 443, 8080 | 3 |
| [2606:4700:440f:df65:4c77:19ea:c42b:96d2] | 80, 443, 8080 | 4 |
| [2606:4700:440f:df65:4c77:19ea:c42b:96d2] | 80, 443, 8080 | 4 |
| [2606:4700:440f:df65:4c77:19ea:c42b:96d2] | 80, 443, 8080 | 4 |
| [2606:4700:8ca5:ebd:60e8:c4eb:bdf1:d873] | 80, 443, 8080 | 136 |
| [2606:4700:8ca5:ebd:60e8:c4eb:bdf1:d873] | 80, 443, 8080 | 136 |
| [2606:4700:8ca5:ebd:60e8:c4eb:bdf1:d873] | 80, 443, 8080 | 136 |

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
