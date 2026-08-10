# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-11 00:41:24 +0330

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
| 198.41.209.137 | 80, 443, 8080 | 50 |
| 198.41.209.137 | 80, 443, 8080 | 50 |
| 198.41.208.72 | 80, 443, 8080 | 53 |
| 198.41.209.207 | 80, 443, 8080 | 53 |
| 198.41.208.72 | 80, 443, 8080 | 53 |
| 198.41.209.207 | 80, 443, 8080 | 53 |
| 198.41.209.58 | 80, 443, 8080 | 54 |
| 198.41.209.58 | 80, 443, 8080 | 54 |
| 104.17.22.237 | 80, 443, 8080 | 138 |
| 104.18.67.129 | 80, 443, 8080 | 138 |
| 104.19.39.197 | 80, 443, 8080 | 138 |
| 104.17.200.244 | 80, 443, 8080 | 138 |
| 172.64.81.121 | 80, 443, 8080 | 139 |
| 172.64.89.145 | 80, 443, 8080 | 179 |
| 172.64.89.145 | 80, 443, 8080 | 179 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dee:573d:c495:3b0b:8b78:6cfa] | 80, 443, 8080 | 0 |
| [2606:4700:839e:a4d8:af2d:c404:124d:f1fc] | 80, 443, 8080 | 0 |
| [2606:4700:9a67:79c8:29b1:abd9:368f:b207] | 80, 443, 8080 | 0 |
| [2606:4700:8dee:573d:c495:3b0b:8b78:6cfa] | 80, 443, 8080 | 0 |
| [2606:4700:839e:a4d8:af2d:c404:124d:f1fc] | 80, 443, 8080 | 0 |
| [2606:4700:9a67:79c8:29b1:abd9:368f:b207] | 80, 443, 8080 | 0 |
| [2606:4700:8dee:573d:c495:3b0b:8b78:6cfa] | 80, 443, 8080 | 0 |
| [2606:4700:839e:a4d8:af2d:c404:124d:f1fc] | 80, 443, 8080 | 0 |
| [2606:4700:9a67:79c8:29b1:abd9:368f:b207] | 80, 443, 8080 | 0 |
| [2606:4700:839e:867b:a3b5:2f31:de28:96c9] | 80, 443, 8080 | 1 |
| [2606:4700:9a67:14a9:6250:b51f:4db0:f55e] | 80, 443, 8080 | 1 |
| [2606:4700:839e:867b:a3b5:2f31:de28:96c9] | 80, 443, 8080 | 1 |
| [2606:4700:9a67:14a9:6250:b51f:4db0:f55e] | 80, 443, 8080 | 1 |
| [2606:4700:839e:867b:a3b5:2f31:de28:96c9] | 80, 443, 8080 | 1 |
| [2606:4700:9a67:14a9:6250:b51f:4db0:f55e] | 80, 443, 8080 | 1 |

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
