# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-30 16:50:50 +0330

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
| 198.41.209.26 | 80, 443, 8080 | 49 |
| 198.41.209.26 | 80, 443, 8080 | 49 |
| 198.41.208.195 | 80, 443, 8080 | 50 |
| 198.41.208.195 | 80, 443, 8080 | 50 |
| 198.41.208.207 | 80, 443, 8080 | 51 |
| 198.41.208.207 | 80, 443, 8080 | 51 |
| 198.41.208.201 | 80, 443, 8080 | 75 |
| 198.41.208.201 | 80, 443, 8080 | 75 |
| 104.18.204.236 | 80, 443, 8080 | 143 |
| 104.18.204.5 | 80, 443, 8080 | 143 |
| 104.18.211.24 | 80, 443, 8080 | 143 |
| 104.16.214.145 | 80, 443, 8080 | 144 |
| 104.18.246.194 | 80, 443, 8080 | 148 |
| 162.159.160.250 | 80, 443, 8080 | 158 |
| 162.159.160.250 | 80, 443, 8080 | 158 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9add:46a9:9381:48d8:6847:4903] | 80, 443, 8080 | 3 |
| [2606:4700:9ae8:228a:6a03:2344:f20d:b8c0] | 80, 443, 8080 | 3 |
| [2606:4700:9add:46a9:9381:48d8:6847:4903] | 80, 443, 8080 | 3 |
| [2606:4700:9ae8:228a:6a03:2344:f20d:b8c0] | 80, 443, 8080 | 3 |
| [2606:4700:9add:46a9:9381:48d8:6847:4903] | 80, 443, 8080 | 3 |
| [2606:4700:9ae8:228a:6a03:2344:f20d:b8c0] | 80, 443, 8080 | 3 |
| [2606:4700:9ae8:b840:dd45:87a2:dbb0:491] | 80, 443, 8080 | 4 |
| [2606:4700:99ed:d338:b76:14ac:1e0b:916] | 80, 443, 8080 | 4 |
| [2606:4700:9ae8:b840:dd45:87a2:dbb0:491] | 80, 443, 8080 | 4 |
| [2606:4700:99ed:d338:b76:14ac:1e0b:916] | 80, 443, 8080 | 4 |
| [2606:4700:9ae8:b840:dd45:87a2:dbb0:491] | 80, 443, 8080 | 4 |
| [2606:4700:99ed:d338:b76:14ac:1e0b:916] | 80, 443, 8080 | 4 |
| [2606:4700:8ca9:b409:a6c:2fee:6baa:3554] | 80, 443, 8080 | 143 |
| [2606:4700:8ca9:b409:a6c:2fee:6baa:3554] | 80, 443, 8080 | 143 |
| [2606:4700:8ca9:b409:a6c:2fee:6baa:3554] | 80, 443, 8080 | 143 |

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
