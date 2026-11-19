# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-19 19:28:06 +0330

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
| 104.17.56.65 | 80, 443, 8080 | 142 |
| 104.19.152.26 | 80, 443, 8080 | 142 |
| 104.19.204.156 | 80, 443, 8080 | 142 |
| 104.17.244.165 | 80, 443, 8080 | 142 |
| 104.19.19.138 | 80, 443, 8080 | 143 |
| 162.159.160.98 | 80, 443, 8080 | 149 |
| 162.159.160.98 | 80, 443, 8080 | 149 |
| 162.159.160.180 | 80, 443, 8080 | 154 |
| 162.159.160.180 | 80, 443, 8080 | 154 |
| 162.159.160.80 | 80, 443, 8080 | 159 |
| 162.159.160.80 | 80, 443, 8080 | 159 |
| 162.159.138.129 | 80, 443, 8080 | 167 |
| 162.159.133.27 | 80, 443, 8080 | 167 |
| 162.159.138.129 | 80, 443, 8080 | 167 |
| 162.159.133.27 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b05:3876:1ec4:e564:1e02:dc01] | 80, 443, 8080 | 3 |
| [2606:4700:9a92:ed6d:335:19aa:7536:7dea] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:3876:1ec4:e564:1e02:dc01] | 80, 443, 8080 | 3 |
| [2606:4700:9a92:ed6d:335:19aa:7536:7dea] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:3876:1ec4:e564:1e02:dc01] | 80, 443, 8080 | 3 |
| [2606:4700:9a92:ed6d:335:19aa:7536:7dea] | 80, 443, 8080 | 3 |
| [2606:4700:90d2:58e0:1bde:f9a8:1a82:3e26] | 80, 443, 8080 | 4 |
| [2606:4700:90d2:58e0:1bde:f9a8:1a82:3e26] | 80, 443, 8080 | 4 |
| [2606:4700:90d2:58e0:1bde:f9a8:1a82:3e26] | 80, 443, 8080 | 4 |
| [2606:4700:9a62:88f5:ce46:1a20:f79f:a761] | 80, 443, 8080 | 5 |
| [2606:4700:9a62:88f5:ce46:1a20:f79f:a761] | 80, 443, 8080 | 5 |
| [2606:4700:9a62:88f5:ce46:1a20:f79f:a761] | 80, 443, 8080 | 5 |
| [2606:4700:22:11a:33b5:e3d8:d82e:cda1] | 80, 443, 8080 | 13 |
| [2606:4700:22:11a:33b5:e3d8:d82e:cda1] | 80, 443, 8080 | 13 |
| [2606:4700:22:11a:33b5:e3d8:d82e:cda1] | 80, 443, 8080 | 13 |

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
