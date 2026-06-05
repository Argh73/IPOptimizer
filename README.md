# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-05 14:02:22 +0330

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
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.208.108 | 80, 443, 8080 | 56 |
| 198.41.208.108 | 80, 443, 8080 | 56 |
| 198.41.209.106 | 80, 443, 8080 | 59 |
| 198.41.209.106 | 80, 443, 8080 | 59 |
| 198.41.222.115 | 80, 443, 8080 | 67 |
| 104.18.205.202 | 80, 443, 8080 | 130 |
| 104.17.71.98 | 80, 443, 8080 | 130 |
| 104.18.211.125 | 80, 443, 8080 | 133 |
| 190.93.247.163 | 80, 443, 8080 | 133 |
| 162.159.242.186 | 80, 443, 8080 | 178 |
| 162.159.242.186 | 80, 443, 8080 | 178 |
| 162.159.243.163 | 80, 443, 8080 | 179 |
| 162.159.243.163 | 80, 443, 8080 | 179 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:1b:c9c4:405:af1b:20ad:f6dc] | 80, 443, 8080 | 0 |
| [2606:4700:1b:d8e1:3b2:962:a276:bc31] | 80, 443, 8080 | 0 |
| [2606:4700:1b:c9c4:405:af1b:20ad:f6dc] | 80, 443, 8080 | 0 |
| [2606:4700:1b:d8e1:3b2:962:a276:bc31] | 80, 443, 8080 | 0 |
| [2606:4700:1b:c9c4:405:af1b:20ad:f6dc] | 80, 443, 8080 | 0 |
| [2606:4700:1b:d8e1:3b2:962:a276:bc31] | 80, 443, 8080 | 0 |
| [2606:4700:9a96:cd28:8b83:b5af:4e66:2caa] | 80, 443, 8080 | 3 |
| [2606:4700:2f:e8cf:c8bc:3a40:10b6:998] | 80, 443, 8080 | 3 |
| [2606:4700:3012:5603:21c0:b173:5847:93fc] | 80, 443, 8080 | 3 |
| [2606:4700:9a96:cd28:8b83:b5af:4e66:2caa] | 80, 443, 8080 | 3 |
| [2606:4700:2f:e8cf:c8bc:3a40:10b6:998] | 80, 443, 8080 | 3 |
| [2606:4700:3012:5603:21c0:b173:5847:93fc] | 80, 443, 8080 | 3 |
| [2606:4700:9a96:cd28:8b83:b5af:4e66:2caa] | 80, 443, 8080 | 3 |
| [2606:4700:2f:e8cf:c8bc:3a40:10b6:998] | 80, 443, 8080 | 3 |
| [2606:4700:3012:5603:21c0:b173:5847:93fc] | 80, 443, 8080 | 3 |

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
