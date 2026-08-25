# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-25 10:54:59 +0330

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
| 198.41.209.54 | 80, 443, 8080 | 45 |
| 198.41.209.54 | 80, 443, 8080 | 45 |
| 198.41.208.228 | 80, 443, 8080 | 47 |
| 198.41.208.228 | 80, 443, 8080 | 47 |
| 198.41.208.166 | 80, 443, 8080 | 50 |
| 198.41.208.46 | 80, 443, 8080 | 50 |
| 198.41.208.166 | 80, 443, 8080 | 50 |
| 198.41.208.46 | 80, 443, 8080 | 50 |
| 198.41.209.52 | 80, 443, 8080 | 67 |
| 198.41.209.52 | 80, 443, 8080 | 67 |
| 104.17.32.129 | 80, 443, 8080 | 142 |
| 173.245.49.18 | 80, 443, 8080 | 142 |
| 104.17.198.130 | 80, 443, 8080 | 142 |
| 162.159.252.26 | 80, 443, 8080 | 149 |
| 104.17.98.205 | 80, 443, 8080 | 151 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b0e:a745:4eff:bc76:682c:50b] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:a745:4eff:bc76:682c:50b] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:a745:4eff:bc76:682c:50b] | 80, 443, 8080 | 3 |
| [2606:4700:9:2c89:fe8b:db48:7c22:cb37] | 80, 443, 8080 | 4 |
| [2606:4700:9:2c89:fe8b:db48:7c22:cb37] | 80, 443, 8080 | 4 |
| [2606:4700:9:2c89:fe8b:db48:7c22:cb37] | 80, 443, 8080 | 4 |
| [2606:4700:4408:c379:75ec:cd03:de87:f173] | 80, 443, 8080 | 5 |
| [2606:4700:4408:c379:75ec:cd03:de87:f173] | 80, 443, 8080 | 5 |
| [2606:4700:4408:c379:75ec:cd03:de87:f173] | 80, 443, 8080 | 5 |
| [2606:4700:9:6936:bbd6:611:f1c7:5b20] | 80, 443, 8080 | 13 |
| [2606:4700:3017:b0df:d796:66b7:8ae0:6afc] | 80, 443, 8080 | 13 |
| [2606:4700:9:6936:bbd6:611:f1c7:5b20] | 80, 443, 8080 | 13 |
| [2606:4700:3017:b0df:d796:66b7:8ae0:6afc] | 80, 443, 8080 | 13 |
| [2606:4700:9:6936:bbd6:611:f1c7:5b20] | 80, 443, 8080 | 13 |
| [2606:4700:3017:b0df:d796:66b7:8ae0:6afc] | 80, 443, 8080 | 13 |

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
