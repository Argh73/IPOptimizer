# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-07 17:13:38 +0330

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
| 172.67.174.6 | 80, 443, 8080 | 134 |
| 172.67.162.135 | 80, 443, 8080 | 136 |
| 172.67.153.49 | 80, 443, 8080 | 137 |
| 172.67.158.116 | 80, 443, 8080 | 137 |
| 172.67.166.56 | 80, 443, 8080 | 137 |
| 104.18.17.85 | 80, 443, 8080 | 142 |
| 104.16.137.135 | 80, 443, 8080 | 143 |
| 104.19.216.192 | 80, 443, 8080 | 143 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.19.94.12 | 80, 443, 8080 | 148 |
| 104.26.10.226 | 80, 443, 8080 | 149 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d9d:a4e2:31d4:f603:ac6a:fc90] | 80, 443, 8080 | 3 |
| [2606:4700:91bf:cf06:8c5a:5171:eba6:7342] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:d24c:4495:a332:c7af:3749] | 80, 443, 8080 | 3 |
| [2606:4700:91bf:716a:fd40:35fd:9061:41b9] | 80, 443, 8080 | 3 |
| [2606:4700:9ae4:c5e0:83b6:c3e6:21f5:c98b] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:a4e2:31d4:f603:ac6a:fc90] | 80, 443, 8080 | 3 |
| [2606:4700:91bf:cf06:8c5a:5171:eba6:7342] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:d24c:4495:a332:c7af:3749] | 80, 443, 8080 | 3 |
| [2606:4700:91bf:716a:fd40:35fd:9061:41b9] | 80, 443, 8080 | 3 |
| [2606:4700:9ae4:c5e0:83b6:c3e6:21f5:c98b] | 80, 443, 8080 | 3 |
| [2606:4700:8d9d:a4e2:31d4:f603:ac6a:fc90] | 80, 443, 8080 | 3 |
| [2606:4700:91bf:cf06:8c5a:5171:eba6:7342] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:d24c:4495:a332:c7af:3749] | 80, 443, 8080 | 3 |
| [2606:4700:91bf:716a:fd40:35fd:9061:41b9] | 80, 443, 8080 | 3 |
| [2606:4700:9ae4:c5e0:83b6:c3e6:21f5:c98b] | 80, 443, 8080 | 3 |

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
