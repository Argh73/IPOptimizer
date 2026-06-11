# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-12 01:51:51 +0330

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
| 198.41.209.41 | 80, 443, 8080 | 51 |
| 198.41.209.41 | 80, 443, 8080 | 51 |
| 198.41.208.202 | 80, 443, 8080 | 52 |
| 198.41.208.202 | 80, 443, 8080 | 52 |
| 198.41.208.146 | 80, 443, 8080 | 54 |
| 198.41.208.236 | 80, 443, 8080 | 54 |
| 198.41.208.100 | 80, 443, 8080 | 54 |
| 198.41.208.146 | 80, 443, 8080 | 54 |
| 198.41.208.236 | 80, 443, 8080 | 54 |
| 198.41.208.100 | 80, 443, 8080 | 54 |
| 162.159.36.127 | 80, 443, 8080 | 78 |
| 104.16.157.201 | 80, 443, 8080 | 130 |
| 104.17.103.109 | 80, 443, 8080 | 130 |
| 104.17.78.203 | 80, 443, 8080 | 131 |
| 104.16.147.208 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9a9e:8082:7c4f:2bf3:67ca:483f] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:a2b:31ef:9f27:bca1:5626] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:3c08:a1a8:883e:ace9:5faa] | 80, 443, 8080 | 3 |
| [2606:4700:300b:d12e:5268:f8fb:f00b:8215] | 80, 443, 8080 | 3 |
| [2606:4700:300b:6d7d:90e9:5f04:1b46:89fd] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:8082:7c4f:2bf3:67ca:483f] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:a2b:31ef:9f27:bca1:5626] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:3c08:a1a8:883e:ace9:5faa] | 80, 443, 8080 | 3 |
| [2606:4700:300b:d12e:5268:f8fb:f00b:8215] | 80, 443, 8080 | 3 |
| [2606:4700:300b:6d7d:90e9:5f04:1b46:89fd] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:8082:7c4f:2bf3:67ca:483f] | 80, 443, 8080 | 3 |
| [2606:4700:9a9e:a2b:31ef:9f27:bca1:5626] | 80, 443, 8080 | 3 |
| [2606:4700:9b00:3c08:a1a8:883e:ace9:5faa] | 80, 443, 8080 | 3 |
| [2606:4700:300b:d12e:5268:f8fb:f00b:8215] | 80, 443, 8080 | 3 |
| [2606:4700:300b:6d7d:90e9:5f04:1b46:89fd] | 80, 443, 8080 | 3 |

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
