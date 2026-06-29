# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-29 15:02:11 +0330

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
| 198.41.208.202 | 80, 443, 8080 | 52 |
| 198.41.222.79 | 80, 443, 8080 | 71 |
| 198.41.222.79 | 80, 443, 8080 | 71 |
| 198.41.222.79 | 80, 443, 8080 | 71 |
| 104.16.176.127 | 80, 443, 8080 | 130 |
| 104.16.176.127 | 80, 443, 8080 | 130 |
| 104.16.176.127 | 80, 443, 8080 | 130 |
| 104.19.48.34 | 80, 443, 8080 | 132 |
| 104.16.233.117 | 80, 443, 8080 | 132 |
| 104.18.232.3 | 80, 443, 8080 | 132 |
| 104.19.48.34 | 80, 443, 8080 | 132 |
| 104.16.233.117 | 80, 443, 8080 | 132 |
| 104.18.232.3 | 80, 443, 8080 | 132 |
| 104.19.48.34 | 80, 443, 8080 | 132 |
| 104.16.233.117 | 80, 443, 8080 | 132 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91be:1213:71dc:190a:9d69:f8f1] | 80, 443, 8080 | 0 |
| [2606:4700:9c60:4ab5:2b3:eae1:9918:c90] | 80, 443, 8080 | 0 |
| [2606:4700:91be:1213:71dc:190a:9d69:f8f1] | 80, 443, 8080 | 0 |
| [2606:4700:9c60:4ab5:2b3:eae1:9918:c90] | 80, 443, 8080 | 0 |
| [2606:4700:91be:1213:71dc:190a:9d69:f8f1] | 80, 443, 8080 | 0 |
| [2606:4700:9c60:4ab5:2b3:eae1:9918:c90] | 80, 443, 8080 | 0 |
| [2606:4700:91be:fffd:7721:7d21:ca4c:a377] | 80, 443, 8080 | 1 |
| [2606:4700:3006:1d67:9212:519e:b83e:93a] | 80, 443, 8080 | 1 |
| [2606:4700:9a99:9949:e105:42e8:45f3:b72d] | 80, 443, 8080 | 1 |
| [2606:4700:91be:fffd:7721:7d21:ca4c:a377] | 80, 443, 8080 | 1 |
| [2606:4700:3006:1d67:9212:519e:b83e:93a] | 80, 443, 8080 | 1 |
| [2606:4700:9a99:9949:e105:42e8:45f3:b72d] | 80, 443, 8080 | 1 |
| [2606:4700:91be:fffd:7721:7d21:ca4c:a377] | 80, 443, 8080 | 1 |
| [2606:4700:3006:1d67:9212:519e:b83e:93a] | 80, 443, 8080 | 1 |
| [2606:4700:9a99:9949:e105:42e8:45f3:b72d] | 80, 443, 8080 | 1 |

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
