# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-05 04:28:40 +0330

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
| 198.41.208.183 | 80, 443, 8080 | 50 |
| 198.41.209.1 | 80, 443, 8080 | 50 |
| 198.41.208.183 | 80, 443, 8080 | 50 |
| 198.41.209.1 | 80, 443, 8080 | 50 |
| 198.41.208.0 | 80, 443, 8080 | 52 |
| 198.41.208.0 | 80, 443, 8080 | 52 |
| 198.41.208.100 | 80, 443, 8080 | 53 |
| 198.41.208.100 | 80, 443, 8080 | 53 |
| 198.41.209.96 | 80, 443, 8080 | 85 |
| 198.41.209.96 | 80, 443, 8080 | 85 |
| 104.19.218.120 | 80, 443, 8080 | 139 |
| 104.19.4.155 | 80, 443, 8080 | 140 |
| 104.19.57.157 | 80, 443, 8080 | 140 |
| 104.16.251.246 | 80, 443, 8080 | 149 |
| 104.17.48.153 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:964e:b703:2461:c63d:2d1:9dcc] | 80, 443, 8080 | 3 |
| [2606:4700:3037:3037:5eef:5199:4a0b:f2b0] | 80, 443, 8080 | 3 |
| [2606:4700:964e:b703:2461:c63d:2d1:9dcc] | 80, 443, 8080 | 3 |
| [2606:4700:3037:3037:5eef:5199:4a0b:f2b0] | 80, 443, 8080 | 3 |
| [2606:4700:964e:b703:2461:c63d:2d1:9dcc] | 80, 443, 8080 | 3 |
| [2606:4700:3037:3037:5eef:5199:4a0b:f2b0] | 80, 443, 8080 | 3 |
| [2606:4700:3012:72c3:6780:489d:4503:b5f] | 80, 443, 8080 | 13 |
| [2606:4700:3037:42c8:e8a5:92ef:f44b:e37a] | 80, 443, 8080 | 13 |
| [2606:4700:2b:1eaf:a082:44b9:28b:50c5] | 80, 443, 8080 | 13 |
| [2606:4700:3012:72c3:6780:489d:4503:b5f] | 80, 443, 8080 | 13 |
| [2606:4700:3037:42c8:e8a5:92ef:f44b:e37a] | 80, 443, 8080 | 13 |
| [2606:4700:2b:1eaf:a082:44b9:28b:50c5] | 80, 443, 8080 | 13 |
| [2606:4700:3012:72c3:6780:489d:4503:b5f] | 80, 443, 8080 | 13 |
| [2606:4700:3037:42c8:e8a5:92ef:f44b:e37a] | 80, 443, 8080 | 13 |
| [2606:4700:2b:1eaf:a082:44b9:28b:50c5] | 80, 443, 8080 | 13 |

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
