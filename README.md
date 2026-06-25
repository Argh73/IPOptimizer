# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-26 01:31:17 +0330

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
| 198.41.209.161 | 80, 443, 8080 | 39 |
| 198.41.209.161 | 80, 443, 8080 | 39 |
| 198.41.208.174 | 80, 443, 8080 | 41 |
| 198.41.208.174 | 80, 443, 8080 | 41 |
| 198.41.208.55 | 80, 443, 8080 | 51 |
| 198.41.208.55 | 80, 443, 8080 | 51 |
| 198.41.209.50 | 80, 443, 8080 | 52 |
| 198.41.209.50 | 80, 443, 8080 | 52 |
| 198.41.208.202 | 80, 443, 8080 | 53 |
| 198.41.208.202 | 80, 443, 8080 | 53 |
| 104.17.115.121 | 80, 443, 8080 | 130 |
| 104.18.88.121 | 80, 443, 8080 | 130 |
| 104.18.132.184 | 80, 443, 8080 | 130 |
| 104.18.172.247 | 80, 443, 8080 | 130 |
| 104.16.18.210 | 80, 443, 8080 | 130 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9ad2:8c23:517e:4dad:428b:2a25] | 80, 443, 8080 | 0 |
| [2606:4700:9ad2:8c23:517e:4dad:428b:2a25] | 80, 443, 8080 | 0 |
| [2606:4700:9ad2:8c23:517e:4dad:428b:2a25] | 80, 443, 8080 | 0 |
| [2606:4700:99ed:491e:7ac3:6b90:49ff:423a] | 80, 443, 8080 | 1 |
| [2606:4700:8dd2:aec8:1eb2:61c5:129a:a193] | 80, 443, 8080 | 1 |
| [2606:4700:8dd2:6f91:6431:f776:e83e:1e84] | 80, 443, 8080 | 1 |
| [2606:4700:8d95:9d3f:744a:eb9f:66b4:5d9c] | 80, 443, 8080 | 1 |
| [2606:4700:99ed:491e:7ac3:6b90:49ff:423a] | 80, 443, 8080 | 1 |
| [2606:4700:8dd2:aec8:1eb2:61c5:129a:a193] | 80, 443, 8080 | 1 |
| [2606:4700:8dd2:6f91:6431:f776:e83e:1e84] | 80, 443, 8080 | 1 |
| [2606:4700:8d95:9d3f:744a:eb9f:66b4:5d9c] | 80, 443, 8080 | 1 |
| [2606:4700:99ed:491e:7ac3:6b90:49ff:423a] | 80, 443, 8080 | 1 |
| [2606:4700:8dd2:aec8:1eb2:61c5:129a:a193] | 80, 443, 8080 | 1 |
| [2606:4700:8dd2:6f91:6431:f776:e83e:1e84] | 80, 443, 8080 | 1 |
| [2606:4700:8d95:9d3f:744a:eb9f:66b4:5d9c] | 80, 443, 8080 | 1 |

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
