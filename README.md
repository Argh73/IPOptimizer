# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-14 11:27:24 +0330

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
| 198.41.208.20 | 80, 443, 8080 | 55 |
| 198.41.209.16 | 80, 443, 8080 | 55 |
| 198.41.208.20 | 80, 443, 8080 | 55 |
| 198.41.209.16 | 80, 443, 8080 | 55 |
| 198.41.209.48 | 80, 443, 8080 | 56 |
| 198.41.209.48 | 80, 443, 8080 | 56 |
| 198.41.208.204 | 80, 443, 8080 | 142 |
| 104.16.157.53 | 80, 443, 8080 | 142 |
| 172.64.66.84 | 80, 443, 8080 | 142 |
| 104.17.102.64 | 80, 443, 8080 | 142 |
| 104.19.43.196 | 80, 443, 8080 | 142 |
| 198.41.208.204 | 80, 443, 8080 | 142 |
| 104.18.76.190 | 80, 443, 8080 | 144 |
| 172.67.231.35 | 80, 443, 8080 | 181 |
| 172.67.231.35 | 80, 443, 8080 | 181 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:17:4f59:6545:734f:a6b1:fd4d] | 80, 443, 8080 | 0 |
| [2606:4700:91b4:7497:957e:fed2:750e:7123] | 80, 443, 8080 | 0 |
| [2606:4700:17:4f59:6545:734f:a6b1:fd4d] | 80, 443, 8080 | 0 |
| [2606:4700:91b4:7497:957e:fed2:750e:7123] | 80, 443, 8080 | 0 |
| [2606:4700:17:4f59:6545:734f:a6b1:fd4d] | 80, 443, 8080 | 0 |
| [2606:4700:91b4:7497:957e:fed2:750e:7123] | 80, 443, 8080 | 0 |
| [2606:4700:3020:ec12:194e:f932:7555:f86e] | 80, 443, 8080 | 1 |
| [2606:4700:3020:58fc:748f:fe76:ff10:f2d1] | 80, 443, 8080 | 1 |
| [2606:4700:3020:ec12:194e:f932:7555:f86e] | 80, 443, 8080 | 1 |
| [2606:4700:3020:58fc:748f:fe76:ff10:f2d1] | 80, 443, 8080 | 1 |
| [2606:4700:3020:ec12:194e:f932:7555:f86e] | 80, 443, 8080 | 1 |
| [2606:4700:3020:58fc:748f:fe76:ff10:f2d1] | 80, 443, 8080 | 1 |
| [2606:4700:8ca2:243a:9617:7101:19e6:b9e7] | 80, 443, 8080 | 134 |
| [2606:4700:8ca2:243a:9617:7101:19e6:b9e7] | 80, 443, 8080 | 134 |
| [2606:4700:8ca2:243a:9617:7101:19e6:b9e7] | 80, 443, 8080 | 134 |

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
