# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-09 20:14:26 +0330

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
| 198.41.209.254 | 80, 443, 8080 | 56 |
| 198.41.209.254 | 80, 443, 8080 | 56 |
| 198.41.209.185 | 80, 443, 8080 | 72 |
| 198.41.209.185 | 80, 443, 8080 | 72 |
| 198.41.209.130 | 80, 443, 8080 | 91 |
| 198.41.209.130 | 80, 443, 8080 | 91 |
| 172.67.164.173 | 80, 443, 8080 | 139 |
| 172.67.164.173 | 80, 443, 8080 | 139 |
| 104.16.164.184 | 80, 443, 8080 | 142 |
| 104.16.140.149 | 80, 443, 8080 | 142 |
| 104.17.92.16 | 80, 443, 8080 | 142 |
| 104.19.207.72 | 80, 443, 8080 | 142 |
| 104.18.122.226 | 80, 443, 8080 | 143 |
| 198.41.209.216 | 80, 443, 8080 | 144 |
| 198.41.209.216 | 80, 443, 8080 | 144 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ae0:8f79:f22f:abfb:de4d:323a] | 80, 443, 8080 | 3 |
| [2606:4700:9ae0:5b49:2e1c:9a25:3dc3:de3c] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:b6d4:6463:70b9:a40c:3290] | 80, 443, 8080 | 3 |
| [2606:4700:9ae0:8f79:f22f:abfb:de4d:323a] | 80, 443, 8080 | 3 |
| [2606:4700:9ae0:5b49:2e1c:9a25:3dc3:de3c] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:b6d4:6463:70b9:a40c:3290] | 80, 443, 8080 | 3 |
| [2606:4700:9ae0:8f79:f22f:abfb:de4d:323a] | 80, 443, 8080 | 3 |
| [2606:4700:9ae0:5b49:2e1c:9a25:3dc3:de3c] | 80, 443, 8080 | 3 |
| [2606:4700:8de7:b6d4:6463:70b9:a40c:3290] | 80, 443, 8080 | 3 |
| [2606:4700:90cf:9193:8248:11a6:f70b:2002] | 80, 443, 8080 | 5 |
| [2606:4700:9b0b:8cb1:ca58:aadd:5729:e16e] | 80, 443, 8080 | 5 |
| [2606:4700:90cf:9193:8248:11a6:f70b:2002] | 80, 443, 8080 | 5 |
| [2606:4700:9b0b:8cb1:ca58:aadd:5729:e16e] | 80, 443, 8080 | 5 |
| [2606:4700:90cf:9193:8248:11a6:f70b:2002] | 80, 443, 8080 | 5 |
| [2606:4700:9b0b:8cb1:ca58:aadd:5729:e16e] | 80, 443, 8080 | 5 |

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
