# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-19 14:35:00 +0330

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
| 198.41.209.17 | 80, 443, 8080 | 53 |
| 198.41.209.17 | 80, 443, 8080 | 53 |
| 198.41.208.181 | 80, 443, 8080 | 54 |
| 198.41.208.45 | 80, 443, 8080 | 54 |
| 198.41.208.181 | 80, 443, 8080 | 54 |
| 198.41.208.45 | 80, 443, 8080 | 54 |
| 198.41.208.182 | 80, 443, 8080 | 55 |
| 198.41.208.182 | 80, 443, 8080 | 55 |
| 198.41.222.51 | 80, 443, 8080 | 72 |
| 104.18.15.70 | 80, 443, 8080 | 130 |
| 104.18.102.229 | 80, 443, 8080 | 131 |
| 104.18.69.191 | 80, 443, 8080 | 133 |
| 104.16.222.80 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3108:419:ddd1:dce6:3651:edd2] | 80, 443, 8080 | 3 |
| [2606:4700:8ca1:1ee2:a316:8a27:ca7e:9dcc] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:538:6c3f:de88:96bb:5b4] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:8a8e:1e49:577b:d6a0:3d2d] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:813:6131:4cae:d0d6:b384] | 80, 443, 8080 | 3 |
| [2606:4700:3108:419:ddd1:dce6:3651:edd2] | 80, 443, 8080 | 3 |
| [2606:4700:8ca1:1ee2:a316:8a27:ca7e:9dcc] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:538:6c3f:de88:96bb:5b4] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:8a8e:1e49:577b:d6a0:3d2d] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:813:6131:4cae:d0d6:b384] | 80, 443, 8080 | 3 |
| [2606:4700:3108:419:ddd1:dce6:3651:edd2] | 80, 443, 8080 | 3 |
| [2606:4700:8ca1:1ee2:a316:8a27:ca7e:9dcc] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:538:6c3f:de88:96bb:5b4] | 80, 443, 8080 | 3 |
| [2606:4700:91b7:8a8e:1e49:577b:d6a0:3d2d] | 80, 443, 8080 | 3 |
| [2606:4700:8d78:813:6131:4cae:d0d6:b384] | 80, 443, 8080 | 3 |

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
