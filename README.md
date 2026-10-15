# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-16 02:40:06 +0330

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
| 198.41.208.181 | 80, 443, 8080 | 49 |
| 198.41.209.199 | 80, 443, 8080 | 49 |
| 198.41.209.174 | 80, 443, 8080 | 52 |
| 198.41.209.171 | 80, 443, 8080 | 52 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.211.2 | 80, 443, 8080 | 67 |
| 104.17.171.233 | 80, 443, 8080 | 144 |
| 104.16.130.237 | 80, 443, 8080 | 144 |
| 104.18.206.128 | 80, 443, 8080 | 145 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.16.163.126 | 80, 443, 8080 | 146 |
| 162.159.160.162 | 80, 443, 8080 | 160 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d7f:c35a:31e:cbfc:cc31:7db9] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:ff61:b207:f10a:52a4:48e4] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:6261:d8b6:e7f9:aadb:1f36] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:c1c4:cad9:e289:a2cb:c270] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:c35a:31e:cbfc:cc31:7db9] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:ff61:b207:f10a:52a4:48e4] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:6261:d8b6:e7f9:aadb:1f36] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:c1c4:cad9:e289:a2cb:c270] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:c35a:31e:cbfc:cc31:7db9] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:ff61:b207:f10a:52a4:48e4] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:6261:d8b6:e7f9:aadb:1f36] | 80, 443, 8080 | 3 |
| [2606:4700:8d7f:c1c4:cad9:e289:a2cb:c270] | 80, 443, 8080 | 3 |
| [2606:4700:90c2:e0cc:20ea:6e30:c384:ee16] | 80, 443, 8080 | 143 |
| [2606:4700:90c2:e0cc:20ea:6e30:c384:ee16] | 80, 443, 8080 | 143 |
| [2606:4700:90c2:e0cc:20ea:6e30:c384:ee16] | 80, 443, 8080 | 143 |

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
