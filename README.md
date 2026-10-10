# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-10 03:42:22 +0330

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
| 198.41.209.133 | 80, 443, 8080 | 51 |
| 198.41.208.103 | 80, 443, 8080 | 52 |
| 198.41.208.85 | 80, 443, 8080 | 53 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 172.67.161.174 | 80, 443, 8080 | 137 |
| 104.18.207.61 | 80, 443, 8080 | 139 |
| 104.18.14.69 | 80, 443, 8080 | 139 |
| 104.17.177.153 | 80, 443, 8080 | 139 |
| 104.18.81.41 | 80, 443, 8080 | 139 |
| 172.64.84.121 | 80, 443, 8080 | 142 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 172.67.168.75 | 80, 443, 8080 | 161 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a99:fec4:1ef3:a482:5e8c:92d2] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:8afb:dc24:c397:961e:81de] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:7f10:ae13:7f7:854b:3865] | 80, 443, 8080 | 3 |
| [2606:4700:9a99:fec4:1ef3:a482:5e8c:92d2] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:8afb:dc24:c397:961e:81de] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:7f10:ae13:7f7:854b:3865] | 80, 443, 8080 | 3 |
| [2606:4700:9a99:fec4:1ef3:a482:5e8c:92d2] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:8afb:dc24:c397:961e:81de] | 80, 443, 8080 | 3 |
| [2606:4700:8d9e:7f10:ae13:7f7:854b:3865] | 80, 443, 8080 | 3 |
| [2606:4700:90c3:64e1:dc8e:edc0:9cde:6532] | 80, 443, 8080 | 153 |
| [2606:4700:90c3:c8c8:f85:859d:89b3:9fbe] | 80, 443, 8080 | 153 |
| [2606:4700:90c3:64e1:dc8e:edc0:9cde:6532] | 80, 443, 8080 | 153 |
| [2606:4700:90c3:c8c8:f85:859d:89b3:9fbe] | 80, 443, 8080 | 153 |
| [2606:4700:90c3:64e1:dc8e:edc0:9cde:6532] | 80, 443, 8080 | 153 |
| [2606:4700:90c3:c8c8:f85:859d:89b3:9fbe] | 80, 443, 8080 | 153 |

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
