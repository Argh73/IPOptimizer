# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-09-12 02:12:43 +0330

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
| 198.41.209.86 | 80, 443, 8080 | 46 |
| 198.41.209.86 | 80, 443, 8080 | 46 |
| 198.41.209.72 | 80, 443, 8080 | 49 |
| 198.41.209.72 | 80, 443, 8080 | 49 |
| 198.41.222.166 | 80, 443, 8080 | 70 |
| 172.67.155.45 | 80, 443, 8080 | 133 |
| 172.67.155.45 | 80, 443, 8080 | 133 |
| 104.19.42.83 | 80, 443, 8080 | 138 |
| 104.16.183.58 | 80, 443, 8080 | 138 |
| 104.19.22.255 | 80, 443, 8080 | 138 |
| 104.18.9.73 | 80, 443, 8080 | 138 |
| 198.41.208.156 | 80, 443, 8080 | 145 |
| 198.41.208.156 | 80, 443, 8080 | 145 |
| 172.67.79.114 | 80, 443, 8080 | 158 |
| 172.67.79.114 | 80, 443, 8080 | 158 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:91bd:80f2:6865:863:7fb9:c0e5] | 80, 443, 8080 | 3 |
| [2606:4700:8d7c:9f76:e601:6175:6413:f369] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:ca15:a875:5077:c902:58b9] | 80, 443, 8080 | 3 |
| [2606:4700:8d7c:eb4c:9d35:aeff:76ac:aefa] | 80, 443, 8080 | 3 |
| [2606:4700:3004:e79b:de6:6a61:bfdc:348] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:80f2:6865:863:7fb9:c0e5] | 80, 443, 8080 | 3 |
| [2606:4700:8d7c:9f76:e601:6175:6413:f369] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:ca15:a875:5077:c902:58b9] | 80, 443, 8080 | 3 |
| [2606:4700:8d7c:eb4c:9d35:aeff:76ac:aefa] | 80, 443, 8080 | 3 |
| [2606:4700:3004:e79b:de6:6a61:bfdc:348] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:80f2:6865:863:7fb9:c0e5] | 80, 443, 8080 | 3 |
| [2606:4700:8d7c:9f76:e601:6175:6413:f369] | 80, 443, 8080 | 3 |
| [2606:4700:91bd:ca15:a875:5077:c902:58b9] | 80, 443, 8080 | 3 |
| [2606:4700:8d7c:eb4c:9d35:aeff:76ac:aefa] | 80, 443, 8080 | 3 |
| [2606:4700:3004:e79b:de6:6a61:bfdc:348] | 80, 443, 8080 | 3 |

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
