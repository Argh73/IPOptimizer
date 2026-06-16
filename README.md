# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-06-17 01:59:34 +0330

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
| 198.41.208.78 | 80, 443, 8080 | 54 |
| 198.41.208.78 | 80, 443, 8080 | 54 |
| 198.41.208.32 | 80, 443, 8080 | 55 |
| 198.41.208.32 | 80, 443, 8080 | 55 |
| 198.41.208.106 | 80, 443, 8080 | 68 |
| 198.41.208.106 | 80, 443, 8080 | 68 |
| 104.17.86.62 | 80, 443, 8080 | 129 |
| 104.17.65.189 | 80, 443, 8080 | 130 |
| 104.18.90.230 | 80, 443, 8080 | 130 |
| 104.16.15.234 | 80, 443, 8080 | 130 |
| 104.17.22.79 | 80, 443, 8080 | 131 |
| 172.67.160.101 | 80, 443, 8080 | 191 |
| 172.67.160.101 | 80, 443, 8080 | 191 |
| 172.67.70.77 | 80, 443, 8080 | 194 |
| 172.67.70.77 | 80, 443, 8080 | 194 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:23:55c3:81c6:e1b3:9e14:bea3] | 80, 443, 8080 | 3 |
| [2606:4700:9aed:930:a69:b028:947:db99] | 80, 443, 8080 | 3 |
| [2606:4700:9a61:fcb4:56d9:c8df:762f:a8f] | 80, 443, 8080 | 3 |
| [2606:4700:3033:e19e:20c3:54be:a0e1:78e6] | 80, 443, 8080 | 3 |
| [2606:4700:23:55c3:81c6:e1b3:9e14:bea3] | 80, 443, 8080 | 3 |
| [2606:4700:9aed:930:a69:b028:947:db99] | 80, 443, 8080 | 3 |
| [2606:4700:9a61:fcb4:56d9:c8df:762f:a8f] | 80, 443, 8080 | 3 |
| [2606:4700:3033:e19e:20c3:54be:a0e1:78e6] | 80, 443, 8080 | 3 |
| [2606:4700:23:55c3:81c6:e1b3:9e14:bea3] | 80, 443, 8080 | 3 |
| [2606:4700:9aed:930:a69:b028:947:db99] | 80, 443, 8080 | 3 |
| [2606:4700:9a61:fcb4:56d9:c8df:762f:a8f] | 80, 443, 8080 | 3 |
| [2606:4700:3033:e19e:20c3:54be:a0e1:78e6] | 80, 443, 8080 | 3 |
| [2606:4700:3016:97b0:ce3f:f64e:646f:da5c] | 80, 443, 8080 | 13 |
| [2606:4700:3016:97b0:ce3f:f64e:646f:da5c] | 80, 443, 8080 | 13 |
| [2606:4700:3016:97b0:ce3f:f64e:646f:da5c] | 80, 443, 8080 | 13 |

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
