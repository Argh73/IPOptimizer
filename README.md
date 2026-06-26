# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-26 13:28:16 +0330

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
| 198.41.209.161 | 80, 443, 8080 | 39 |
| 198.41.209.161 | 80, 443, 8080 | 39 |
| 198.41.208.174 | 80, 443, 8080 | 41 |
| 198.41.208.174 | 80, 443, 8080 | 41 |
| 198.41.208.55 | 80, 443, 8080 | 51 |
| 198.41.208.55 | 80, 443, 8080 | 51 |
| 198.41.209.50 | 80, 443, 8080 | 52 |
| 198.41.209.50 | 80, 443, 8080 | 52 |
| 198.41.208.202 | 80, 443, 8080 | 53 |
| 198.41.208.202 | 80, 443, 8080 | 53 |
| 198.41.223.188 | 80, 443, 8080 | 71 |
| 104.18.169.140 | 80, 443, 8080 | 129 |
| 104.16.223.222 | 80, 443, 8080 | 130 |
| 104.16.110.164 | 80, 443, 8080 | 131 |
| 104.19.178.156 | 80, 443, 8080 | 132 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b0e:8f99:24b5:3346:28bd:5889] | 80, 443, 8080 | 0 |
| [2606:4700:9b0e:8f99:24b5:3346:28bd:5889] | 80, 443, 8080 | 0 |
| [2606:4700:9b0e:8f99:24b5:3346:28bd:5889] | 80, 443, 8080 | 0 |
| [2606:4700:9b02:449a:e92b:6f1d:5b50:2020] | 80, 443, 8080 | 1 |
| [2606:4700:8cad:b199:b4ac:98c2:9512:d97b] | 80, 443, 8080 | 1 |
| [2606:4700:9b02:eaa4:c2de:71d5:ba34:918a] | 80, 443, 8080 | 1 |
| [2606:4700:8ded:2918:6ca6:c11b:afe4:93b0] | 80, 443, 8080 | 1 |
| [2606:4700:9b02:449a:e92b:6f1d:5b50:2020] | 80, 443, 8080 | 1 |
| [2606:4700:8cad:b199:b4ac:98c2:9512:d97b] | 80, 443, 8080 | 1 |
| [2606:4700:9b02:eaa4:c2de:71d5:ba34:918a] | 80, 443, 8080 | 1 |
| [2606:4700:8ded:2918:6ca6:c11b:afe4:93b0] | 80, 443, 8080 | 1 |
| [2606:4700:9b02:449a:e92b:6f1d:5b50:2020] | 80, 443, 8080 | 1 |
| [2606:4700:8cad:b199:b4ac:98c2:9512:d97b] | 80, 443, 8080 | 1 |
| [2606:4700:9b02:eaa4:c2de:71d5:ba34:918a] | 80, 443, 8080 | 1 |
| [2606:4700:8ded:2918:6ca6:c11b:afe4:93b0] | 80, 443, 8080 | 1 |

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
