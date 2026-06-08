# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-08 14:56:15 +0330

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
| 162.159.46.150 | 80, 443, 8080 | 71 |
| 162.159.46.150 | 80, 443, 8080 | 71 |
| 162.159.46.150 | 80, 443, 8080 | 71 |
| 162.159.36.50 | 80, 443, 8080 | 75 |
| 162.159.36.50 | 80, 443, 8080 | 75 |
| 162.159.36.50 | 80, 443, 8080 | 75 |
| 104.18.184.149 | 80, 443, 8080 | 130 |
| 104.18.184.149 | 80, 443, 8080 | 130 |
| 104.18.184.149 | 80, 443, 8080 | 130 |
| 104.17.57.70 | 80, 443, 8080 | 131 |
| 104.17.57.70 | 80, 443, 8080 | 131 |
| 104.17.57.70 | 80, 443, 8080 | 131 |
| 104.19.64.110 | 80, 443, 8080 | 133 |
| 104.19.64.110 | 80, 443, 8080 | 133 |
| 104.19.64.110 | 80, 443, 8080 | 133 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:839d:2ea9:4dff:65a1:a144:7aaa] | 80, 443, 8080 | 3 |
| [2606:4700:9b0c:e17:2ddc:30ca:5133:7431] | 80, 443, 8080 | 3 |
| [2606:4700:9642:a26e:6270:cd64:577:eb45] | 80, 443, 8080 | 3 |
| [2606:4700:839d:2ea9:4dff:65a1:a144:7aaa] | 80, 443, 8080 | 3 |
| [2606:4700:9b0c:e17:2ddc:30ca:5133:7431] | 80, 443, 8080 | 3 |
| [2606:4700:9642:a26e:6270:cd64:577:eb45] | 80, 443, 8080 | 3 |
| [2606:4700:839d:2ea9:4dff:65a1:a144:7aaa] | 80, 443, 8080 | 3 |
| [2606:4700:9b0c:e17:2ddc:30ca:5133:7431] | 80, 443, 8080 | 3 |
| [2606:4700:9642:a26e:6270:cd64:577:eb45] | 80, 443, 8080 | 3 |
| [2606:4700:c:4b67:f993:268b:4037:c15a] | 80, 443, 8080 | 4 |
| [2606:4700:c:4b67:f993:268b:4037:c15a] | 80, 443, 8080 | 4 |
| [2606:4700:c:4b67:f993:268b:4037:c15a] | 80, 443, 8080 | 4 |
| [2606:4700:9b0c:9efb:8a9e:91d:d328:80a9] | 80, 443, 8080 | 5 |
| [2606:4700:9b0c:9efb:8a9e:91d:d328:80a9] | 80, 443, 8080 | 5 |
| [2606:4700:9b0c:9efb:8a9e:91d:d328:80a9] | 80, 443, 8080 | 5 |

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
