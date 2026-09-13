# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-13 15:42:24 +0330

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
| 198.41.209.85 | 80, 443, 8080 | 48 |
| 198.41.209.85 | 80, 443, 8080 | 48 |
| 198.41.209.179 | 80, 443, 8080 | 49 |
| 198.41.209.135 | 80, 443, 8080 | 49 |
| 198.41.208.48 | 80, 443, 8080 | 49 |
| 198.41.209.179 | 80, 443, 8080 | 49 |
| 198.41.209.135 | 80, 443, 8080 | 49 |
| 198.41.208.48 | 80, 443, 8080 | 49 |
| 198.41.211.208 | 80, 443, 8080 | 76 |
| 198.41.208.83 | 80, 443, 8080 | 78 |
| 198.41.208.83 | 80, 443, 8080 | 78 |
| 104.19.63.203 | 80, 443, 8080 | 138 |
| 104.17.248.209 | 80, 443, 8080 | 141 |
| 104.18.228.166 | 80, 443, 8080 | 141 |
| 104.21.225.214 | 80, 443, 8080 | 143 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:4407:76e4:b74c:65db:9960:9474] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:71b9:4a0f:231c:ee3d:f2ba] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:51c2:c22e:2c9e:a91c:ba9f] | 80, 443, 8080 | 3 |
| [2606:4700:4407:76e4:b74c:65db:9960:9474] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:71b9:4a0f:231c:ee3d:f2ba] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:51c2:c22e:2c9e:a91c:ba9f] | 80, 443, 8080 | 3 |
| [2606:4700:4407:76e4:b74c:65db:9960:9474] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:71b9:4a0f:231c:ee3d:f2ba] | 80, 443, 8080 | 3 |
| [2606:4700:9ae9:51c2:c22e:2c9e:a91c:ba9f] | 80, 443, 8080 | 3 |
| [2606:4700:4407:3eac:19b1:7282:3b80:530d] | 80, 443, 8080 | 13 |
| [2606:4700:4407:3eac:19b1:7282:3b80:530d] | 80, 443, 8080 | 13 |
| [2606:4700:4407:3eac:19b1:7282:3b80:530d] | 80, 443, 8080 | 13 |
| [2606:4700:83b8:3e14:c8d1:3c08:de6d:e8d8] | 80, 443, 8080 | 166 |
| [2606:4700:83b8:3e14:c8d1:3c08:de6d:e8d8] | 80, 443, 8080 | 166 |
| [2606:4700:83b8:3e14:c8d1:3c08:de6d:e8d8] | 80, 443, 8080 | 166 |

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
