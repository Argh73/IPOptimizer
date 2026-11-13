# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-13 18:18:49 +0330

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
| 104.17.104.134 | 80, 443, 8080 | 143 |
| 104.19.42.154 | 80, 443, 8080 | 143 |
| 104.16.0.195 | 80, 443, 8080 | 144 |
| 104.16.145.72 | 80, 443, 8080 | 144 |
| 141.101.121.254 | 80, 443, 8080 | 151 |
| 162.159.160.69 | 80, 443, 8080 | 156 |
| 162.159.160.69 | 80, 443, 8080 | 156 |
| 162.159.160.211 | 80, 443, 8080 | 157 |
| 162.159.160.211 | 80, 443, 8080 | 157 |
| 162.159.152.251 | 80, 443, 8080 | 165 |
| 162.159.152.251 | 80, 443, 8080 | 165 |
| 162.159.133.1 | 80, 443, 8080 | 166 |
| 162.159.135.219 | 80, 443, 8080 | 166 |
| 162.159.133.1 | 80, 443, 8080 | 166 |
| 162.159.135.219 | 80, 443, 8080 | 166 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:3018:437b:ecaa:a2d3:b734:93f3] | 80, 443, 8080 | 3 |
| [2606:4700:83bd:f7da:fc74:d19d:b62b:2f7b] | 80, 443, 8080 | 3 |
| [2606:4700:83bd:f43e:675e:e838:6d2d:c5c7] | 80, 443, 8080 | 3 |
| [2606:4700:90dc:552a:43c4:c86c:52a8:c689] | 80, 443, 8080 | 3 |
| [2606:4700:3018:437b:ecaa:a2d3:b734:93f3] | 80, 443, 8080 | 3 |
| [2606:4700:83bd:f7da:fc74:d19d:b62b:2f7b] | 80, 443, 8080 | 3 |
| [2606:4700:83bd:f43e:675e:e838:6d2d:c5c7] | 80, 443, 8080 | 3 |
| [2606:4700:90dc:552a:43c4:c86c:52a8:c689] | 80, 443, 8080 | 3 |
| [2606:4700:3018:437b:ecaa:a2d3:b734:93f3] | 80, 443, 8080 | 3 |
| [2606:4700:83bd:f7da:fc74:d19d:b62b:2f7b] | 80, 443, 8080 | 3 |
| [2606:4700:83bd:f43e:675e:e838:6d2d:c5c7] | 80, 443, 8080 | 3 |
| [2606:4700:90dc:552a:43c4:c86c:52a8:c689] | 80, 443, 8080 | 3 |
| [2606:4700:3007:9d22:9a30:e977:796a:49f1] | 80, 443, 8080 | 13 |
| [2606:4700:3007:9d22:9a30:e977:796a:49f1] | 80, 443, 8080 | 13 |
| [2606:4700:3007:9d22:9a30:e977:796a:49f1] | 80, 443, 8080 | 13 |

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
