# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-07 16:25:40 +0330

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
| 198.41.209.206 | 80, 443, 8080 | 51 |
| 198.41.209.141 | 80, 443, 8080 | 51 |
| 198.41.209.206 | 80, 443, 8080 | 51 |
| 198.41.209.141 | 80, 443, 8080 | 51 |
| 198.41.208.93 | 80, 443, 8080 | 53 |
| 198.41.208.93 | 80, 443, 8080 | 53 |
| 198.41.208.44 | 80, 443, 8080 | 61 |
| 198.41.208.44 | 80, 443, 8080 | 61 |
| 198.41.209.180 | 80, 443, 8080 | 75 |
| 198.41.209.180 | 80, 443, 8080 | 75 |
| 104.18.131.56 | 80, 443, 8080 | 141 |
| 198.41.215.161 | 80, 443, 8080 | 141 |
| 104.19.65.95 | 80, 443, 8080 | 142 |
| 104.19.16.98 | 80, 443, 8080 | 143 |
| 104.17.252.238 | 80, 443, 8080 | 147 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90d0:b478:6323:9423:1436:3281] | 80, 443, 8080 | 3 |
| [2606:4700:9765:bdc8:1e8e:8af:3029:fbc2] | 80, 443, 8080 | 3 |
| [2606:4700:139:4b82:be6c:5155:ede3:c51a] | 80, 443, 8080 | 3 |
| [2606:4700:90d0:b478:6323:9423:1436:3281] | 80, 443, 8080 | 3 |
| [2606:4700:9765:bdc8:1e8e:8af:3029:fbc2] | 80, 443, 8080 | 3 |
| [2606:4700:139:4b82:be6c:5155:ede3:c51a] | 80, 443, 8080 | 3 |
| [2606:4700:90d0:b478:6323:9423:1436:3281] | 80, 443, 8080 | 3 |
| [2606:4700:9765:bdc8:1e8e:8af:3029:fbc2] | 80, 443, 8080 | 3 |
| [2606:4700:139:4b82:be6c:5155:ede3:c51a] | 80, 443, 8080 | 3 |
| [2606:4700:440e:cc55:c680:a71a:c291:64de] | 80, 443, 8080 | 13 |
| [2606:4700:440e:cc55:c680:a71a:c291:64de] | 80, 443, 8080 | 13 |
| [2606:4700:440e:cc55:c680:a71a:c291:64de] | 80, 443, 8080 | 13 |
| [2606:4700:83ba:3b00:9487:5e88:3588:6494] | 80, 443, 8080 | 158 |
| [2606:4700:83ba:3b00:9487:5e88:3588:6494] | 80, 443, 8080 | 158 |
| [2606:4700:83ba:3b00:9487:5e88:3588:6494] | 80, 443, 8080 | 158 |

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
