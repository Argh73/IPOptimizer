# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-16 15:16:08 +0330

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
| 198.41.208.31 | 80, 443, 8080 | 48 |
| 198.41.208.31 | 80, 443, 8080 | 48 |
| 198.41.209.127 | 80, 443, 8080 | 50 |
| 198.41.209.183 | 80, 443, 8080 | 50 |
| 198.41.209.127 | 80, 443, 8080 | 50 |
| 198.41.209.183 | 80, 443, 8080 | 50 |
| 198.41.208.115 | 80, 443, 8080 | 51 |
| 198.41.208.115 | 80, 443, 8080 | 51 |
| 198.41.208.193 | 80, 443, 8080 | 52 |
| 198.41.208.193 | 80, 443, 8080 | 52 |
| 104.18.227.19 | 80, 443, 8080 | 141 |
| 104.17.30.198 | 80, 443, 8080 | 143 |
| 104.18.238.117 | 80, 443, 8080 | 144 |
| 104.17.96.168 | 80, 443, 8080 | 144 |
| 104.19.216.78 | 80, 443, 8080 | 146 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ae3:3406:9352:e598:e88:fc5f] | 80, 443, 8080 | 3 |
| [2606:4700:839e:3dea:55dc:dd9d:a6e7:b85] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:d15e:4fff:3913:7a0d:e404] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:7036:1873:d508:d7cf:9ed2] | 80, 443, 8080 | 3 |
| [2606:4700:9ae3:3406:9352:e598:e88:fc5f] | 80, 443, 8080 | 3 |
| [2606:4700:839e:3dea:55dc:dd9d:a6e7:b85] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:d15e:4fff:3913:7a0d:e404] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:7036:1873:d508:d7cf:9ed2] | 80, 443, 8080 | 3 |
| [2606:4700:9ae3:3406:9352:e598:e88:fc5f] | 80, 443, 8080 | 3 |
| [2606:4700:839e:3dea:55dc:dd9d:a6e7:b85] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:d15e:4fff:3913:7a0d:e404] | 80, 443, 8080 | 3 |
| [2606:4700:9ad7:7036:1873:d508:d7cf:9ed2] | 80, 443, 8080 | 3 |
| [2606:4700:9b05:c42f:628a:3e34:5a25:ae0a] | 80, 443, 8080 | 5 |
| [2606:4700:9b05:c42f:628a:3e34:5a25:ae0a] | 80, 443, 8080 | 5 |
| [2606:4700:9b05:c42f:628a:3e34:5a25:ae0a] | 80, 443, 8080 | 5 |

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
