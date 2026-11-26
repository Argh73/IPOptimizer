# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-26 20:42:26 +0330

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
| 104.16.0.195 | 80, 443, 8080 | 141 |
| 104.16.239.220 | 80, 443, 8080 | 142 |
| 104.18.102.236 | 80, 443, 8080 | 142 |
| 104.18.141.167 | 80, 443, 8080 | 143 |
| 104.19.20.226 | 80, 443, 8080 | 143 |
| 162.159.160.206 | 80, 443, 8080 | 157 |
| 162.159.160.206 | 80, 443, 8080 | 157 |
| 162.159.134.54 | 80, 443, 8080 | 163 |
| 162.159.134.54 | 80, 443, 8080 | 163 |
| 162.159.137.10 | 80, 443, 8080 | 164 |
| 162.159.137.10 | 80, 443, 8080 | 164 |
| 162.159.138.115 | 80, 443, 8080 | 165 |
| 162.159.133.154 | 80, 443, 8080 | 165 |
| 162.159.138.115 | 80, 443, 8080 | 165 |
| 162.159.133.154 | 80, 443, 8080 | 165 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9640:ba1:46c8:391c:2d45:6283] | 80, 443, 8080 | 3 |
| [2606:4700:9640:3989:6df0:44ab:75b:a5d5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:4603:1977:2b1:e075:7790] | 80, 443, 8080 | 3 |
| [2606:4700:9645:197a:1cbd:1c5f:1c20:bee4] | 80, 443, 8080 | 3 |
| [2606:4700:9aec:d828:4449:d6d9:ff64:d791] | 80, 443, 8080 | 3 |
| [2606:4700:9640:ba1:46c8:391c:2d45:6283] | 80, 443, 8080 | 3 |
| [2606:4700:9640:3989:6df0:44ab:75b:a5d5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:4603:1977:2b1:e075:7790] | 80, 443, 8080 | 3 |
| [2606:4700:9645:197a:1cbd:1c5f:1c20:bee4] | 80, 443, 8080 | 3 |
| [2606:4700:9aec:d828:4449:d6d9:ff64:d791] | 80, 443, 8080 | 3 |
| [2606:4700:9640:ba1:46c8:391c:2d45:6283] | 80, 443, 8080 | 3 |
| [2606:4700:9640:3989:6df0:44ab:75b:a5d5] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:4603:1977:2b1:e075:7790] | 80, 443, 8080 | 3 |
| [2606:4700:9645:197a:1cbd:1c5f:1c20:bee4] | 80, 443, 8080 | 3 |
| [2606:4700:9aec:d828:4449:d6d9:ff64:d791] | 80, 443, 8080 | 3 |

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
