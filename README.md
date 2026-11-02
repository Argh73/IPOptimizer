# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-11-02 19:56:31 +0330

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
| 198.41.209.6 | 80, 443, 8080 | 74 |
| 198.41.209.6 | 80, 443, 8080 | 74 |
| 198.41.208.238 | 80, 443, 8080 | 111 |
| 198.41.208.238 | 80, 443, 8080 | 111 |
| 104.19.20.162 | 80, 443, 8080 | 142 |
| 104.18.148.55 | 80, 443, 8080 | 142 |
| 104.19.112.99 | 80, 443, 8080 | 142 |
| 104.19.67.52 | 80, 443, 8080 | 142 |
| 104.19.163.208 | 80, 443, 8080 | 142 |
| 162.159.160.20 | 80, 443, 8080 | 155 |
| 162.159.160.20 | 80, 443, 8080 | 155 |
| 162.159.135.239 | 80, 443, 8080 | 163 |
| 162.159.135.239 | 80, 443, 8080 | 163 |
| 162.159.129.55 | 80, 443, 8080 | 165 |
| 162.159.129.55 | 80, 443, 8080 | 165 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:90d5:5c53:acc7:3763:9770:702f] | 80, 443, 8080 | 3 |
| [2606:4700:e:6b10:4de1:83b5:bf14:15af] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:1cb3:f58a:434d:fbb3:6c70] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:5c53:acc7:3763:9770:702f] | 80, 443, 8080 | 3 |
| [2606:4700:e:6b10:4de1:83b5:bf14:15af] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:1cb3:f58a:434d:fbb3:6c70] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:5c53:acc7:3763:9770:702f] | 80, 443, 8080 | 3 |
| [2606:4700:e:6b10:4de1:83b5:bf14:15af] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:1cb3:f58a:434d:fbb3:6c70] | 80, 443, 8080 | 3 |
| [2606:4700:e:6c50:990e:cc3:41b5:108d] | 80, 443, 8080 | 13 |
| [2606:4700:e:6c50:990e:cc3:41b5:108d] | 80, 443, 8080 | 13 |
| [2606:4700:e:6c50:990e:cc3:41b5:108d] | 80, 443, 8080 | 13 |
| [2606:4700:13a:87da:adcb:9b29:de53:be12] | 80, 443, 8080 | 19 |
| [2606:4700:13a:87da:adcb:9b29:de53:be12] | 80, 443, 8080 | 19 |
| [2606:4700:13a:87da:adcb:9b29:de53:be12] | 80, 443, 8080 | 19 |

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
