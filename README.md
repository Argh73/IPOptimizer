# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-15 01:21:28 +0330

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
| 198.41.209.110 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.208.186 | 80, 443, 8080 | 51 |
| 198.41.209.110 | 80, 443, 8080 | 51 |
| 198.41.209.186 | 80, 443, 8080 | 51 |
| 198.41.208.186 | 80, 443, 8080 | 51 |
| 198.41.209.10 | 80, 443, 8080 | 52 |
| 198.41.209.132 | 80, 443, 8080 | 52 |
| 198.41.209.10 | 80, 443, 8080 | 52 |
| 198.41.209.132 | 80, 443, 8080 | 52 |
| 198.41.211.252 | 80, 443, 8080 | 70 |
| 162.159.46.30 | 80, 443, 8080 | 80 |
| 104.19.2.230 | 80, 443, 8080 | 130 |
| 104.18.246.242 | 80, 443, 8080 | 130 |
| 104.17.232.121 | 80, 443, 8080 | 130 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c6f:d1f1:27f0:dcd0:f4bc:a01d] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:7a0f:b184:7d2e:593c:3406] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:d1f1:27f0:dcd0:f4bc:a01d] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:7a0f:b184:7d2e:593c:3406] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:d1f1:27f0:dcd0:f4bc:a01d] | 80, 443, 8080 | 0 |
| [2606:4700:9c6f:7a0f:b184:7d2e:593c:3406] | 80, 443, 8080 | 0 |
| [2606:4700:9b04:84b1:3263:c02e:4ff2:cc0] | 80, 443, 8080 | 3 |
| [2606:4700:9b04:84b1:3263:c02e:4ff2:cc0] | 80, 443, 8080 | 3 |
| [2606:4700:9b04:84b1:3263:c02e:4ff2:cc0] | 80, 443, 8080 | 3 |
| [2606:4700:9b04:e0a6:4c9d:aecf:ff2f:431] | 80, 443, 8080 | 4 |
| [2606:4700:9b04:e0a6:4c9d:aecf:ff2f:431] | 80, 443, 8080 | 4 |
| [2606:4700:9b04:e0a6:4c9d:aecf:ff2f:431] | 80, 443, 8080 | 4 |
| [2606:4700:964e:a033:6bf:9fee:62d5:7351] | 80, 443, 8080 | 5 |
| [2606:4700:964e:a033:6bf:9fee:62d5:7351] | 80, 443, 8080 | 5 |
| [2606:4700:964e:a033:6bf:9fee:62d5:7351] | 80, 443, 8080 | 5 |

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
