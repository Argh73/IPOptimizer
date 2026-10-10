# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-10 16:23:17 +0330

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
| 198.41.223.207 | 80, 443, 8080 | 70 |
| 198.41.208.227 | 80, 443, 8080 | 80 |
| 172.67.166.96 | 80, 443, 8080 | 134 |
| 172.67.70.4 | 80, 443, 8080 | 135 |
| 172.67.149.165 | 80, 443, 8080 | 136 |
| 172.67.156.180 | 80, 443, 8080 | 138 |
| 104.19.27.252 | 80, 443, 8080 | 142 |
| 162.159.193.104 | 80, 443, 8080 | 142 |
| 104.16.20.150 | 80, 443, 8080 | 143 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.17.166.4 | 80, 443, 8080 | 149 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90d9:5dd4:18d0:b8e9:3f24:924c] | 80, 443, 8080 | 3 |
| [2606:4700:83bf:1d02:1634:5643:eb71:586d] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:ae3a:ee5e:ccd6:1ccd:ffcf] | 80, 443, 8080 | 3 |
| [2606:4700:3037:f853:dbd9:cdb1:d87b:d098] | 80, 443, 8080 | 3 |
| [2606:4700:90d9:5dd4:18d0:b8e9:3f24:924c] | 80, 443, 8080 | 3 |
| [2606:4700:83bf:1d02:1634:5643:eb71:586d] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:ae3a:ee5e:ccd6:1ccd:ffcf] | 80, 443, 8080 | 3 |
| [2606:4700:3037:f853:dbd9:cdb1:d87b:d098] | 80, 443, 8080 | 3 |
| [2606:4700:90d9:5dd4:18d0:b8e9:3f24:924c] | 80, 443, 8080 | 3 |
| [2606:4700:83bf:1d02:1634:5643:eb71:586d] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:ae3a:ee5e:ccd6:1ccd:ffcf] | 80, 443, 8080 | 3 |
| [2606:4700:3037:f853:dbd9:cdb1:d87b:d098] | 80, 443, 8080 | 3 |
| [2606:4700:3037:338f:cf01:c691:5a0:a90a] | 80, 443, 8080 | 13 |
| [2606:4700:3037:338f:cf01:c691:5a0:a90a] | 80, 443, 8080 | 13 |
| [2606:4700:3037:338f:cf01:c691:5a0:a90a] | 80, 443, 8080 | 13 |

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
