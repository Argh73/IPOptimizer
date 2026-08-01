# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-01 12:09:48 +0330

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
| 198.41.208.218 | 80, 443, 8080 | 50 |
| 198.41.208.218 | 80, 443, 8080 | 50 |
| 198.41.209.137 | 80, 443, 8080 | 51 |
| 198.41.209.110 | 80, 443, 8080 | 51 |
| 198.41.209.137 | 80, 443, 8080 | 51 |
| 198.41.209.110 | 80, 443, 8080 | 51 |
| 198.41.208.63 | 80, 443, 8080 | 53 |
| 198.41.208.63 | 80, 443, 8080 | 53 |
| 198.41.208.163 | 80, 443, 8080 | 56 |
| 198.41.208.163 | 80, 443, 8080 | 56 |
| 104.17.151.123 | 80, 443, 8080 | 151 |
| 104.18.221.90 | 80, 443, 8080 | 151 |
| 104.19.210.110 | 80, 443, 8080 | 154 |
| 104.17.238.78 | 80, 443, 8080 | 154 |
| 104.21.9.184 | 80, 443, 8080 | 169 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ae0:86c7:162c:d15b:49a9:62f3] | 80, 443, 8080 | 0 |
| [2606:4700:3010:40ed:47fd:bb21:e4fd:e74e] | 80, 443, 8080 | 0 |
| [2606:4700:3032:1729:ef50:adc2:5695:7881] | 80, 443, 8080 | 0 |
| [2606:4700:9ae0:86c7:162c:d15b:49a9:62f3] | 80, 443, 8080 | 0 |
| [2606:4700:3010:40ed:47fd:bb21:e4fd:e74e] | 80, 443, 8080 | 0 |
| [2606:4700:3032:1729:ef50:adc2:5695:7881] | 80, 443, 8080 | 0 |
| [2606:4700:9ae0:86c7:162c:d15b:49a9:62f3] | 80, 443, 8080 | 0 |
| [2606:4700:3010:40ed:47fd:bb21:e4fd:e74e] | 80, 443, 8080 | 0 |
| [2606:4700:3032:1729:ef50:adc2:5695:7881] | 80, 443, 8080 | 0 |
| [2606:4700:8dee:a82f:5678:9f41:f12a:c11e] | 80, 443, 8080 | 1 |
| [2606:4700:3010:de48:9da7:6bd6:9a91:414b] | 80, 443, 8080 | 1 |
| [2606:4700:8dee:a82f:5678:9f41:f12a:c11e] | 80, 443, 8080 | 1 |
| [2606:4700:3010:de48:9da7:6bd6:9a91:414b] | 80, 443, 8080 | 1 |
| [2606:4700:8dee:a82f:5678:9f41:f12a:c11e] | 80, 443, 8080 | 1 |
| [2606:4700:3010:de48:9da7:6bd6:9a91:414b] | 80, 443, 8080 | 1 |

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
