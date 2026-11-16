# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-16 03:39:23 +0330

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
| 172.64.85.124 | 80, 443, 8080 | 138 |
| 104.18.1.153 | 80, 443, 8080 | 138 |
| 104.17.165.118 | 80, 443, 8080 | 139 |
| 104.16.207.174 | 80, 443, 8080 | 139 |
| 104.17.60.51 | 80, 443, 8080 | 139 |
| 162.159.160.156 | 80, 443, 8080 | 148 |
| 162.159.160.156 | 80, 443, 8080 | 148 |
| 162.159.160.6 | 80, 443, 8080 | 154 |
| 162.159.160.6 | 80, 443, 8080 | 154 |
| 162.159.160.27 | 80, 443, 8080 | 155 |
| 162.159.160.27 | 80, 443, 8080 | 155 |
| 162.159.137.10 | 80, 443, 8080 | 165 |
| 162.159.137.10 | 80, 443, 8080 | 165 |
| 162.159.130.234 | 80, 443, 8080 | 167 |
| 162.159.130.234 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:4405:e705:a643:962c:63b:930] | 80, 443, 8080 | 3 |
| [2606:4700:90d0:e210:44b2:6a78:106c:9254] | 80, 443, 8080 | 3 |
| [2606:4700:99ed:5fef:8789:4598:159f:5703] | 80, 443, 8080 | 3 |
| [2606:4700:90da:ca21:b16b:d453:66ab:ae19] | 80, 443, 8080 | 3 |
| [2606:4700:4405:e705:a643:962c:63b:930] | 80, 443, 8080 | 3 |
| [2606:4700:90d0:e210:44b2:6a78:106c:9254] | 80, 443, 8080 | 3 |
| [2606:4700:99ed:5fef:8789:4598:159f:5703] | 80, 443, 8080 | 3 |
| [2606:4700:90da:ca21:b16b:d453:66ab:ae19] | 80, 443, 8080 | 3 |
| [2606:4700:4405:e705:a643:962c:63b:930] | 80, 443, 8080 | 3 |
| [2606:4700:90d0:e210:44b2:6a78:106c:9254] | 80, 443, 8080 | 3 |
| [2606:4700:99ed:5fef:8789:4598:159f:5703] | 80, 443, 8080 | 3 |
| [2606:4700:90da:ca21:b16b:d453:66ab:ae19] | 80, 443, 8080 | 3 |
| [2606:4700:4405:8d49:ed55:e8bc:56aa:b490] | 80, 443, 8080 | 13 |
| [2606:4700:4405:8d49:ed55:e8bc:56aa:b490] | 80, 443, 8080 | 13 |
| [2606:4700:4405:8d49:ed55:e8bc:56aa:b490] | 80, 443, 8080 | 13 |

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
