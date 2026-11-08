# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-08 17:15:06 +0330

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
| 198.41.209.48 | 80, 443, 8080 | 53 |
| 198.41.209.48 | 80, 443, 8080 | 53 |
| 198.41.208.168 | 80, 443, 8080 | 55 |
| 198.41.208.168 | 80, 443, 8080 | 55 |
| 198.41.208.23 | 80, 443, 8080 | 77 |
| 198.41.208.23 | 80, 443, 8080 | 77 |
| 172.67.173.28 | 80, 443, 8080 | 138 |
| 172.67.173.28 | 80, 443, 8080 | 138 |
| 104.17.157.241 | 80, 443, 8080 | 142 |
| 104.17.62.224 | 80, 443, 8080 | 142 |
| 104.19.101.190 | 80, 443, 8080 | 142 |
| 162.159.240.175 | 80, 443, 8080 | 142 |
| 104.17.57.254 | 80, 443, 8080 | 142 |
| 172.67.172.3 | 80, 443, 8080 | 147 |
| 172.67.172.3 | 80, 443, 8080 | 147 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d9d:403:67ec:2e23:6c4a:3966] | 80, 443, 8080 | 3 |
| [2606:4700:8d79:c493:3e0:dde2:8e53:5ed1] | 80, 443, 8080 | 3 |
| [2606:4700:9aee:4eea:2ffc:f0ea:c271:71af] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:ca4b:d213:1b3f:5bd:2547] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:403:67ec:2e23:6c4a:3966] | 80, 443, 8080 | 3 |
| [2606:4700:8d79:c493:3e0:dde2:8e53:5ed1] | 80, 443, 8080 | 3 |
| [2606:4700:9aee:4eea:2ffc:f0ea:c271:71af] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:ca4b:d213:1b3f:5bd:2547] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:403:67ec:2e23:6c4a:3966] | 80, 443, 8080 | 3 |
| [2606:4700:8d79:c493:3e0:dde2:8e53:5ed1] | 80, 443, 8080 | 3 |
| [2606:4700:9aee:4eea:2ffc:f0ea:c271:71af] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:ca4b:d213:1b3f:5bd:2547] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:fe91:ccf5:adcd:95bd:ed84] | 80, 443, 8080 | 4 |
| [2606:4700:9c66:fe91:ccf5:adcd:95bd:ed84] | 80, 443, 8080 | 4 |
| [2606:4700:9c66:fe91:ccf5:adcd:95bd:ed84] | 80, 443, 8080 | 4 |

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
