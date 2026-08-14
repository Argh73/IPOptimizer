# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-15 00:25:24 +0330

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
| 198.41.208.251 | 80, 443, 8080 | 53 |
| 198.41.208.251 | 80, 443, 8080 | 53 |
| 198.41.208.228 | 80, 443, 8080 | 54 |
| 198.41.208.228 | 80, 443, 8080 | 54 |
| 198.41.209.22 | 80, 443, 8080 | 56 |
| 198.41.209.22 | 80, 443, 8080 | 56 |
| 104.19.238.112 | 80, 443, 8080 | 138 |
| 104.16.203.150 | 80, 443, 8080 | 138 |
| 172.64.84.185 | 80, 443, 8080 | 138 |
| 104.18.191.41 | 80, 443, 8080 | 139 |
| 104.17.119.237 | 80, 443, 8080 | 139 |
| 162.159.250.203 | 80, 443, 8080 | 180 |
| 172.67.107.103 | 80, 443, 8080 | 180 |
| 162.159.250.203 | 80, 443, 8080 | 180 |
| 172.67.107.103 | 80, 443, 8080 | 180 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8d78:ac7c:b486:b61b:4a7e:ae23] | 80, 443, 8080 | 0 |
| [2606:4700:3032:c6e9:c8dc:2877:80a0:7e0a] | 80, 443, 8080 | 0 |
| [2606:4700:8d78:ac7c:b486:b61b:4a7e:ae23] | 80, 443, 8080 | 0 |
| [2606:4700:3032:c6e9:c8dc:2877:80a0:7e0a] | 80, 443, 8080 | 0 |
| [2606:4700:8d78:ac7c:b486:b61b:4a7e:ae23] | 80, 443, 8080 | 0 |
| [2606:4700:3032:c6e9:c8dc:2877:80a0:7e0a] | 80, 443, 8080 | 0 |
| [2606:4700:8d78:6fa7:463e:853e:ec49:3f3d] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:2f4c:52b4:1c91:f880:3a43] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:34b3:d944:898a:1c5b:af16] | 80, 443, 8080 | 1 |
| [2606:4700:8d78:6fa7:463e:853e:ec49:3f3d] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:2f4c:52b4:1c91:f880:3a43] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:34b3:d944:898a:1c5b:af16] | 80, 443, 8080 | 1 |
| [2606:4700:8d78:6fa7:463e:853e:ec49:3f3d] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:2f4c:52b4:1c91:f880:3a43] | 80, 443, 8080 | 1 |
| [2606:4700:8d92:34b3:d944:898a:1c5b:af16] | 80, 443, 8080 | 1 |

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
