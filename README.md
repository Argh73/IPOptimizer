# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-04 18:16:39 +0330

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
| 198.41.208.231 | 80, 443, 8080 | 58 |
| 198.41.208.231 | 80, 443, 8080 | 58 |
| 198.41.209.124 | 80, 443, 8080 | 61 |
| 198.41.209.124 | 80, 443, 8080 | 61 |
| 198.41.209.223 | 80, 443, 8080 | 95 |
| 198.41.209.223 | 80, 443, 8080 | 95 |
| 198.41.209.29 | 80, 443, 8080 | 111 |
| 198.41.209.29 | 80, 443, 8080 | 111 |
| 104.19.120.252 | 80, 443, 8080 | 142 |
| 104.18.141.122 | 80, 443, 8080 | 142 |
| 104.16.254.183 | 80, 443, 8080 | 142 |
| 104.18.22.201 | 80, 443, 8080 | 142 |
| 104.16.255.93 | 80, 443, 8080 | 150 |
| 162.159.136.47 | 80, 443, 8080 | 164 |
| 162.159.136.47 | 80, 443, 8080 | 164 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b0a:b3d:b377:cb23:812c:a4d0] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:f71:82fd:b906:4501:5917] | 80, 443, 8080 | 3 |
| [2606:4700:90dd:779c:142d:9b78:1ba:4755] | 80, 443, 8080 | 3 |
| [2606:4700:9644:330a:88d3:b9c0:2779:a4a6] | 80, 443, 8080 | 3 |
| [2606:4700:9640:336a:8f72:3c7b:a911:3098] | 80, 443, 8080 | 3 |
| [2606:4700:9b0a:b3d:b377:cb23:812c:a4d0] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:f71:82fd:b906:4501:5917] | 80, 443, 8080 | 3 |
| [2606:4700:90dd:779c:142d:9b78:1ba:4755] | 80, 443, 8080 | 3 |
| [2606:4700:9644:330a:88d3:b9c0:2779:a4a6] | 80, 443, 8080 | 3 |
| [2606:4700:9640:336a:8f72:3c7b:a911:3098] | 80, 443, 8080 | 3 |
| [2606:4700:9b0a:b3d:b377:cb23:812c:a4d0] | 80, 443, 8080 | 3 |
| [2606:4700:8d98:f71:82fd:b906:4501:5917] | 80, 443, 8080 | 3 |
| [2606:4700:90dd:779c:142d:9b78:1ba:4755] | 80, 443, 8080 | 3 |
| [2606:4700:9644:330a:88d3:b9c0:2779:a4a6] | 80, 443, 8080 | 3 |
| [2606:4700:9640:336a:8f72:3c7b:a911:3098] | 80, 443, 8080 | 3 |

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
