# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-23 22:07:30 +0330

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
| 104.16.1.182 | 80, 443, 8080 | 142 |
| 104.16.10.178 | 80, 443, 8080 | 142 |
| 104.19.203.71 | 80, 443, 8080 | 142 |
| 104.16.224.207 | 80, 443, 8080 | 143 |
| 104.16.1.88 | 80, 443, 8080 | 143 |
| 162.159.160.60 | 80, 443, 8080 | 147 |
| 162.159.160.60 | 80, 443, 8080 | 147 |
| 162.159.129.178 | 80, 443, 8080 | 165 |
| 162.159.128.113 | 80, 443, 8080 | 165 |
| 162.159.129.178 | 80, 443, 8080 | 165 |
| 162.159.128.113 | 80, 443, 8080 | 165 |
| 162.159.128.16 | 80, 443, 8080 | 166 |
| 162.159.128.65 | 80, 443, 8080 | 166 |
| 162.159.128.16 | 80, 443, 8080 | 166 |
| 162.159.128.65 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8caf:f46c:b3:1689:7a9b:2410] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:1129:bc5f:3551:d9ab:a7cb] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:e4df:1ff3:e5e8:38c8:5d02] | 80, 443, 8080 | 3 |
| [2606:4700:9ad0:e9bb:785f:b087:2a92:f913] | 80, 443, 8080 | 3 |
| [2606:4700:8caf:f46c:b3:1689:7a9b:2410] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:1129:bc5f:3551:d9ab:a7cb] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:e4df:1ff3:e5e8:38c8:5d02] | 80, 443, 8080 | 3 |
| [2606:4700:9ad0:e9bb:785f:b087:2a92:f913] | 80, 443, 8080 | 3 |
| [2606:4700:8caf:f46c:b3:1689:7a9b:2410] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:1129:bc5f:3551:d9ab:a7cb] | 80, 443, 8080 | 3 |
| [2606:4700:9b03:e4df:1ff3:e5e8:38c8:5d02] | 80, 443, 8080 | 3 |
| [2606:4700:9ad0:e9bb:785f:b087:2a92:f913] | 80, 443, 8080 | 3 |
| [2606:4700:3002:a274:8d4b:2b7d:891e:70e4] | 80, 443, 8080 | 13 |
| [2606:4700:3002:a274:8d4b:2b7d:891e:70e4] | 80, 443, 8080 | 13 |
| [2606:4700:3002:a274:8d4b:2b7d:891e:70e4] | 80, 443, 8080 | 13 |

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
