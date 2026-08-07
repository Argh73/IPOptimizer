# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-07 11:21:59 +0330

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
| 198.41.209.114 | 80, 443, 8080 | 55 |
| 198.41.209.114 | 80, 443, 8080 | 55 |
| 198.41.208.141 | 80, 443, 8080 | 124 |
| 198.41.208.141 | 80, 443, 8080 | 124 |
| 104.18.229.205 | 80, 443, 8080 | 142 |
| 104.18.72.45 | 80, 443, 8080 | 142 |
| 104.16.141.37 | 80, 443, 8080 | 142 |
| 104.16.7.21 | 80, 443, 8080 | 142 |
| 104.16.143.224 | 80, 443, 8080 | 143 |
| 198.41.208.12 | 80, 443, 8080 | 159 |
| 198.41.208.12 | 80, 443, 8080 | 159 |
| 198.41.208.53 | 80, 443, 8080 | 166 |
| 198.41.208.53 | 80, 443, 8080 | 166 |
| 172.67.113.4 | 80, 443, 8080 | 184 |
| 172.67.113.4 | 80, 443, 8080 | 184 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:27:cf9:610:b27e:de4:7051] | 80, 443, 8080 | 0 |
| [2606:4700:8d94:55d4:63ac:1c07:ab40:9352] | 80, 443, 8080 | 0 |
| [2606:4700:27:f504:ac53:de3b:44eb:6ad3] | 80, 443, 8080 | 0 |
| [2606:4700:27:cf9:610:b27e:de4:7051] | 80, 443, 8080 | 0 |
| [2606:4700:8d94:55d4:63ac:1c07:ab40:9352] | 80, 443, 8080 | 0 |
| [2606:4700:27:f504:ac53:de3b:44eb:6ad3] | 80, 443, 8080 | 0 |
| [2606:4700:27:cf9:610:b27e:de4:7051] | 80, 443, 8080 | 0 |
| [2606:4700:8d94:55d4:63ac:1c07:ab40:9352] | 80, 443, 8080 | 0 |
| [2606:4700:27:f504:ac53:de3b:44eb:6ad3] | 80, 443, 8080 | 0 |
| [2606:4700:8d94:8385:bcbe:40f4:cb7d:9872] | 80, 443, 8080 | 1 |
| [2606:4700:91bf:2004:3eec:656a:71e3:8285] | 80, 443, 8080 | 1 |
| [2606:4700:8d94:8385:bcbe:40f4:cb7d:9872] | 80, 443, 8080 | 1 |
| [2606:4700:91bf:2004:3eec:656a:71e3:8285] | 80, 443, 8080 | 1 |
| [2606:4700:8d94:8385:bcbe:40f4:cb7d:9872] | 80, 443, 8080 | 1 |
| [2606:4700:91bf:2004:3eec:656a:71e3:8285] | 80, 443, 8080 | 1 |

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
