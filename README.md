# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-08 01:22:37 +0330

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
| 198.41.209.50 | 80, 443, 8080 | 51 |
| 198.41.209.50 | 80, 443, 8080 | 51 |
| 198.41.209.213 | 80, 443, 8080 | 52 |
| 198.41.209.213 | 80, 443, 8080 | 52 |
| 198.41.209.228 | 80, 443, 8080 | 54 |
| 198.41.209.228 | 80, 443, 8080 | 54 |
| 198.41.209.63 | 80, 443, 8080 | 55 |
| 198.41.209.63 | 80, 443, 8080 | 55 |
| 198.41.222.222 | 80, 443, 8080 | 84 |
| 162.159.36.44 | 80, 443, 8080 | 93 |
| 104.16.23.177 | 80, 443, 8080 | 130 |
| 104.17.181.4 | 80, 443, 8080 | 130 |
| 104.18.69.196 | 80, 443, 8080 | 130 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c64:4cce:b2f0:12db:bd2d:c68f] | 80, 443, 8080 | 0 |
| [2606:4700:91b9:fa90:79cb:7d7f:f70b:deca] | 80, 443, 8080 | 0 |
| [2606:4700:91b9:f7e6:12a7:e7b7:8cd3:a351] | 80, 443, 8080 | 0 |
| [2606:4700:3002:8ed:5b8:12c5:1bc3:1171] | 80, 443, 8080 | 0 |
| [2606:4700:3028:5e01:8f23:a64d:8d4d:50c4] | 80, 443, 8080 | 0 |
| [2606:4700:9c64:4cce:b2f0:12db:bd2d:c68f] | 80, 443, 8080 | 0 |
| [2606:4700:91b9:fa90:79cb:7d7f:f70b:deca] | 80, 443, 8080 | 0 |
| [2606:4700:91b9:f7e6:12a7:e7b7:8cd3:a351] | 80, 443, 8080 | 0 |
| [2606:4700:3002:8ed:5b8:12c5:1bc3:1171] | 80, 443, 8080 | 0 |
| [2606:4700:3028:5e01:8f23:a64d:8d4d:50c4] | 80, 443, 8080 | 0 |
| [2606:4700:9c64:4cce:b2f0:12db:bd2d:c68f] | 80, 443, 8080 | 0 |
| [2606:4700:91b9:fa90:79cb:7d7f:f70b:deca] | 80, 443, 8080 | 0 |
| [2606:4700:91b9:f7e6:12a7:e7b7:8cd3:a351] | 80, 443, 8080 | 0 |
| [2606:4700:3002:8ed:5b8:12c5:1bc3:1171] | 80, 443, 8080 | 0 |
| [2606:4700:3028:5e01:8f23:a64d:8d4d:50c4] | 80, 443, 8080 | 0 |

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
