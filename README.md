# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-10 13:30:21 +0330

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
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.208.163 | 80, 443, 8080 | 54 |
| 198.41.208.76 | 80, 443, 8080 | 54 |
| 198.41.209.145 | 80, 443, 8080 | 59 |
| 198.41.209.145 | 80, 443, 8080 | 59 |
| 162.159.36.217 | 80, 443, 8080 | 89 |
| 104.25.113.64 | 80, 443, 8080 | 164 |
| 104.21.27.244 | 80, 443, 8080 | 166 |
| 104.21.37.204 | 80, 443, 8080 | 166 |
| 162.159.224.220 | 80, 443, 8080 | 168 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:10f:2512:d51d:c89a:f7a8:220b] | 80, 443, 8080 | 3 |
| [2606:4700:91ba:8635:2fa:3128:370d:13ac] | 80, 443, 8080 | 3 |
| [2606:4700:90c1:a071:cf3b:596d:7c2d:945f] | 80, 443, 8080 | 3 |
| [2606:4700:10f:ce3a:a34e:9c18:ac8e:3d85] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f2c6:a7d9:f3d8:2760:fbfd] | 80, 443, 8080 | 3 |
| [2606:4700:10f:2512:d51d:c89a:f7a8:220b] | 80, 443, 8080 | 3 |
| [2606:4700:91ba:8635:2fa:3128:370d:13ac] | 80, 443, 8080 | 3 |
| [2606:4700:90c1:a071:cf3b:596d:7c2d:945f] | 80, 443, 8080 | 3 |
| [2606:4700:10f:ce3a:a34e:9c18:ac8e:3d85] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f2c6:a7d9:f3d8:2760:fbfd] | 80, 443, 8080 | 3 |
| [2606:4700:10f:2512:d51d:c89a:f7a8:220b] | 80, 443, 8080 | 3 |
| [2606:4700:91ba:8635:2fa:3128:370d:13ac] | 80, 443, 8080 | 3 |
| [2606:4700:90c1:a071:cf3b:596d:7c2d:945f] | 80, 443, 8080 | 3 |
| [2606:4700:10f:ce3a:a34e:9c18:ac8e:3d85] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f2c6:a7d9:f3d8:2760:fbfd] | 80, 443, 8080 | 3 |

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
