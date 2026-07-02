# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-02 13:13:13 +0330

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
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.209.154 | 80, 443, 8080 | 53 |
| 198.41.208.67 | 80, 443, 8080 | 56 |
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 198.41.208.67 | 80, 443, 8080 | 56 |
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 162.159.46.141 | 80, 443, 8080 | 71 |
| 104.17.146.238 | 80, 443, 8080 | 131 |
| 104.19.57.246 | 80, 443, 8080 | 131 |
| 104.17.112.49 | 80, 443, 8080 | 133 |
| 104.18.0.16 | 80, 443, 8080 | 133 |
| 172.64.90.119 | 80, 443, 8080 | 181 |
| 172.64.90.119 | 80, 443, 8080 | 181 |
| 172.67.116.63 | 80, 443, 8080 | 184 |
| 172.67.116.63 | 80, 443, 8080 | 184 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dd7:1240:baa4:bf4b:8b59:58b5] | 80, 443, 8080 | 1 |
| [2606:4700:9649:39d0:b6d9:c8f3:9202:1498] | 80, 443, 8080 | 1 |
| [2606:4700:9649:dfa1:a9b9:6434:59e4:80a1] | 80, 443, 8080 | 1 |
| [2606:4700:9ad6:d2f2:2ff:9598:6b5b:5fb5] | 80, 443, 8080 | 1 |
| [2606:4700:9ad6:5cfe:7a74:e2d0:c0:57bd] | 80, 443, 8080 | 1 |
| [2606:4700:8dd7:1240:baa4:bf4b:8b59:58b5] | 80, 443, 8080 | 1 |
| [2606:4700:9649:39d0:b6d9:c8f3:9202:1498] | 80, 443, 8080 | 1 |
| [2606:4700:9649:dfa1:a9b9:6434:59e4:80a1] | 80, 443, 8080 | 1 |
| [2606:4700:9ad6:d2f2:2ff:9598:6b5b:5fb5] | 80, 443, 8080 | 1 |
| [2606:4700:9ad6:5cfe:7a74:e2d0:c0:57bd] | 80, 443, 8080 | 1 |
| [2606:4700:8dd7:1240:baa4:bf4b:8b59:58b5] | 80, 443, 8080 | 1 |
| [2606:4700:9649:39d0:b6d9:c8f3:9202:1498] | 80, 443, 8080 | 1 |
| [2606:4700:9649:dfa1:a9b9:6434:59e4:80a1] | 80, 443, 8080 | 1 |
| [2606:4700:9ad6:d2f2:2ff:9598:6b5b:5fb5] | 80, 443, 8080 | 1 |
| [2606:4700:9ad6:5cfe:7a74:e2d0:c0:57bd] | 80, 443, 8080 | 1 |

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
