# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-11 01:57:01 +0330

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
| 198.41.208.146 | 80, 443, 8080 | 54 |
| 198.41.208.146 | 80, 443, 8080 | 54 |
| 198.41.209.243 | 80, 443, 8080 | 56 |
| 198.41.209.243 | 80, 443, 8080 | 56 |
| 198.41.208.220 | 80, 443, 8080 | 57 |
| 198.41.208.220 | 80, 443, 8080 | 57 |
| 104.19.10.197 | 80, 443, 8080 | 129 |
| 104.19.95.238 | 80, 443, 8080 | 130 |
| 104.17.91.149 | 80, 443, 8080 | 130 |
| 104.16.4.183 | 80, 443, 8080 | 130 |
| 104.18.172.114 | 80, 443, 8080 | 130 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3001:b4ab:25fb:2976:ecbf:5bfb] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:bb27:9a7e:238e:dd7:fdc2] | 80, 443, 8080 | 3 |
| [2606:4700:132:cfd1:2a28:7f35:4794:ec31] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:3df:2fc4:2a:622c:764f] | 80, 443, 8080 | 3 |
| [2606:4700:3001:6865:7e7:3c23:9573:1f4a] | 80, 443, 8080 | 3 |
| [2606:4700:3001:b4ab:25fb:2976:ecbf:5bfb] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:bb27:9a7e:238e:dd7:fdc2] | 80, 443, 8080 | 3 |
| [2606:4700:132:cfd1:2a28:7f35:4794:ec31] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:3df:2fc4:2a:622c:764f] | 80, 443, 8080 | 3 |
| [2606:4700:3001:6865:7e7:3c23:9573:1f4a] | 80, 443, 8080 | 3 |
| [2606:4700:3001:b4ab:25fb:2976:ecbf:5bfb] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:bb27:9a7e:238e:dd7:fdc2] | 80, 443, 8080 | 3 |
| [2606:4700:132:cfd1:2a28:7f35:4794:ec31] | 80, 443, 8080 | 3 |
| [2606:4700:99e0:3df:2fc4:2a:622c:764f] | 80, 443, 8080 | 3 |
| [2606:4700:3001:6865:7e7:3c23:9573:1f4a] | 80, 443, 8080 | 3 |

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
