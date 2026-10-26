# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-26 16:56:29 +0330

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
| 198.41.208.208 | 80, 443, 8080 | 50 |
| 198.41.208.208 | 80, 443, 8080 | 50 |
| 198.41.208.125 | 80, 443, 8080 | 53 |
| 198.41.208.125 | 80, 443, 8080 | 53 |
| 198.41.209.24 | 80, 443, 8080 | 85 |
| 198.41.209.24 | 80, 443, 8080 | 85 |
| 172.67.175.15 | 80, 443, 8080 | 137 |
| 172.67.79.239 | 80, 443, 8080 | 137 |
| 172.67.175.15 | 80, 443, 8080 | 137 |
| 172.67.79.239 | 80, 443, 8080 | 137 |
| 104.18.15.251 | 80, 443, 8080 | 141 |
| 104.19.113.74 | 80, 443, 8080 | 142 |
| 104.16.128.249 | 80, 443, 8080 | 142 |
| 104.18.161.180 | 80, 443, 8080 | 142 |
| 104.16.209.234 | 80, 443, 8080 | 142 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8cae:1967:e150:ec20:11b5:8347] | 80, 443, 8080 | 3 |
| [2606:4700:9adc:e256:d663:4d85:c305:1268] | 80, 443, 8080 | 3 |
| [2606:4700:9643:c28b:63c0:32f6:241e:93e2] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:85dc:3201:69b2:ca29:eb46] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:1967:e150:ec20:11b5:8347] | 80, 443, 8080 | 3 |
| [2606:4700:9adc:e256:d663:4d85:c305:1268] | 80, 443, 8080 | 3 |
| [2606:4700:9643:c28b:63c0:32f6:241e:93e2] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:85dc:3201:69b2:ca29:eb46] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:1967:e150:ec20:11b5:8347] | 80, 443, 8080 | 3 |
| [2606:4700:9adc:e256:d663:4d85:c305:1268] | 80, 443, 8080 | 3 |
| [2606:4700:9643:c28b:63c0:32f6:241e:93e2] | 80, 443, 8080 | 3 |
| [2606:4700:8cae:85dc:3201:69b2:ca29:eb46] | 80, 443, 8080 | 3 |
| [2606:4700:3031:3dc:a8ed:1384:921f:509d] | 80, 443, 8080 | 13 |
| [2606:4700:3031:3dc:a8ed:1384:921f:509d] | 80, 443, 8080 | 13 |
| [2606:4700:3031:3dc:a8ed:1384:921f:509d] | 80, 443, 8080 | 13 |

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
