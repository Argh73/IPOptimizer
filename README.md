# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-09 01:39:33 +0330

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
| 198.41.208.236 | 80, 443, 8080 | 55 |
| 162.159.36.108 | 80, 443, 8080 | 83 |
| 162.159.36.108 | 80, 443, 8080 | 83 |
| 162.159.36.108 | 80, 443, 8080 | 83 |
| 104.16.224.228 | 80, 443, 8080 | 130 |
| 104.16.66.60 | 80, 443, 8080 | 130 |
| 104.18.92.120 | 80, 443, 8080 | 130 |
| 104.16.224.228 | 80, 443, 8080 | 130 |
| 104.16.66.60 | 80, 443, 8080 | 130 |
| 104.18.92.120 | 80, 443, 8080 | 130 |
| 104.16.224.228 | 80, 443, 8080 | 130 |
| 104.16.66.60 | 80, 443, 8080 | 130 |
| 104.18.92.120 | 80, 443, 8080 | 130 |
| 104.16.200.141 | 80, 443, 8080 | 131 |
| 104.16.200.141 | 80, 443, 8080 | 131 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:440d:51a7:3ef:19fe:3da4:3c5e] | 80, 443, 8080 | 3 |
| [2606:4700:440d:bd59:44a3:cc88:9a73:109a] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f11:7f56:5dd3:f739:b9fd] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:f9d0:c368:8f76:95e7:fd9e] | 80, 443, 8080 | 3 |
| [2606:4700:3034:923d:7553:13db:b702:ef05] | 80, 443, 8080 | 3 |
| [2606:4700:440d:51a7:3ef:19fe:3da4:3c5e] | 80, 443, 8080 | 3 |
| [2606:4700:440d:bd59:44a3:cc88:9a73:109a] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f11:7f56:5dd3:f739:b9fd] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:f9d0:c368:8f76:95e7:fd9e] | 80, 443, 8080 | 3 |
| [2606:4700:3034:923d:7553:13db:b702:ef05] | 80, 443, 8080 | 3 |
| [2606:4700:440d:51a7:3ef:19fe:3da4:3c5e] | 80, 443, 8080 | 3 |
| [2606:4700:440d:bd59:44a3:cc88:9a73:109a] | 80, 443, 8080 | 3 |
| [2606:4700:9a68:f11:7f56:5dd3:f739:b9fd] | 80, 443, 8080 | 3 |
| [2606:4700:9ae6:f9d0:c368:8f76:95e7:fd9e] | 80, 443, 8080 | 3 |
| [2606:4700:3034:923d:7553:13db:b702:ef05] | 80, 443, 8080 | 3 |

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
