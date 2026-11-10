# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-10 06:19:58 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 52 |
| 198.41.209.186 | 80, 443, 8080 | 52 |
| 198.41.208.108 | 80, 443, 8080 | 53 |
| 198.41.208.108 | 80, 443, 8080 | 53 |
| 198.41.209.168 | 80, 443, 8080 | 67 |
| 198.41.209.168 | 80, 443, 8080 | 67 |
| 172.67.160.218 | 80, 443, 8080 | 131 |
| 172.67.159.233 | 80, 443, 8080 | 131 |
| 172.67.160.218 | 80, 443, 8080 | 131 |
| 172.67.159.233 | 80, 443, 8080 | 131 |
| 104.17.67.158 | 80, 443, 8080 | 142 |
| 162.159.244.235 | 80, 443, 8080 | 142 |
| 104.17.186.141 | 80, 443, 8080 | 149 |
| 104.16.153.251 | 80, 443, 8080 | 151 |
| 172.67.223.94 | 80, 443, 8080 | 152 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9aea:14d3:81c2:d8aa:1332:ccdb] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:4d74:ebb3:e0f:aa88:c828] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:e934:c058:3cf:ca85:910b] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:eaa4:fc30:b5e7:40a6:1566] | 80, 443, 8080 | 3 |
| [2606:4700:9aea:14d3:81c2:d8aa:1332:ccdb] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:4d74:ebb3:e0f:aa88:c828] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:e934:c058:3cf:ca85:910b] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:eaa4:fc30:b5e7:40a6:1566] | 80, 443, 8080 | 3 |
| [2606:4700:9aea:14d3:81c2:d8aa:1332:ccdb] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:4d74:ebb3:e0f:aa88:c828] | 80, 443, 8080 | 3 |
| [2606:4700:8d77:e934:c058:3cf:ca85:910b] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:eaa4:fc30:b5e7:40a6:1566] | 80, 443, 8080 | 3 |
| [2606:4700:9aec:dffd:943a:dc18:a446:259d] | 80, 443, 8080 | 4 |
| [2606:4700:9aec:dffd:943a:dc18:a446:259d] | 80, 443, 8080 | 4 |
| [2606:4700:9aec:dffd:943a:dc18:a446:259d] | 80, 443, 8080 | 4 |

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
