# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-31 03:26:38 +0330

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
| 198.41.209.70 | 80, 443, 8080 | 48 |
| 198.41.209.70 | 80, 443, 8080 | 48 |
| 198.41.208.75 | 80, 443, 8080 | 50 |
| 198.41.209.108 | 80, 443, 8080 | 50 |
| 198.41.209.112 | 80, 443, 8080 | 50 |
| 198.41.208.75 | 80, 443, 8080 | 50 |
| 198.41.209.108 | 80, 443, 8080 | 50 |
| 198.41.209.112 | 80, 443, 8080 | 50 |
| 104.16.228.69 | 80, 443, 8080 | 138 |
| 162.159.242.60 | 80, 443, 8080 | 138 |
| 104.18.215.128 | 80, 443, 8080 | 139 |
| 104.17.84.2 | 80, 443, 8080 | 139 |
| 104.16.64.45 | 80, 443, 8080 | 139 |
| 141.101.113.235 | 80, 443, 8080 | 169 |
| 141.101.113.235 | 80, 443, 8080 | 169 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b0e:55a0:150d:701e:2483:d63] | 80, 443, 8080 | 3 |
| [2606:4700:9a6d:d8c7:a84c:e96b:b94:226d] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:e1ed:1bc8:8ac2:f9d9:7e9d] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:e397:642e:5872:7197:b3a6] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:55a0:150d:701e:2483:d63] | 80, 443, 8080 | 3 |
| [2606:4700:9a6d:d8c7:a84c:e96b:b94:226d] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:e1ed:1bc8:8ac2:f9d9:7e9d] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:e397:642e:5872:7197:b3a6] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:55a0:150d:701e:2483:d63] | 80, 443, 8080 | 3 |
| [2606:4700:9a6d:d8c7:a84c:e96b:b94:226d] | 80, 443, 8080 | 3 |
| [2606:4700:9b0e:e1ed:1bc8:8ac2:f9d9:7e9d] | 80, 443, 8080 | 3 |
| [2606:4700:9c66:e397:642e:5872:7197:b3a6] | 80, 443, 8080 | 3 |
| [2606:4700:310c:cdce:3cfd:bb1e:ea05:b64c] | 80, 443, 8080 | 4 |
| [2606:4700:310c:cdce:3cfd:bb1e:ea05:b64c] | 80, 443, 8080 | 4 |
| [2606:4700:310c:cdce:3cfd:bb1e:ea05:b64c] | 80, 443, 8080 | 4 |

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
