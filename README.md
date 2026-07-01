# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-07-02 01:29:28 +0330

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
| 198.41.208.67 | 80, 443, 8080 | 56 |
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 198.41.208.67 | 80, 443, 8080 | 56 |
| 198.41.208.44 | 80, 443, 8080 | 56 |
| 162.159.46.202 | 80, 443, 8080 | 66 |
| 162.159.46.234 | 80, 443, 8080 | 72 |
| 104.16.196.105 | 80, 443, 8080 | 129 |
| 104.18.156.217 | 80, 443, 8080 | 130 |
| 104.17.71.137 | 80, 443, 8080 | 130 |
| 172.64.90.119 | 80, 443, 8080 | 181 |
| 172.64.90.119 | 80, 443, 8080 | 181 |
| 172.67.116.63 | 80, 443, 8080 | 184 |
| 172.67.116.63 | 80, 443, 8080 | 184 |
| 172.67.113.59 | 80, 443, 8080 | 187 |
| 172.67.113.59 | 80, 443, 8080 | 187 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9c6c:b9e2:dec6:1339:a4d8:c739] | 80, 443, 8080 | 0 |
| [2606:4700:3009:6b0f:25ab:2c54:6fe5:d67] | 80, 443, 8080 | 0 |
| [2606:4700:9c6c:b9e2:dec6:1339:a4d8:c739] | 80, 443, 8080 | 0 |
| [2606:4700:3009:6b0f:25ab:2c54:6fe5:d67] | 80, 443, 8080 | 0 |
| [2606:4700:9c6c:b9e2:dec6:1339:a4d8:c739] | 80, 443, 8080 | 0 |
| [2606:4700:3009:6b0f:25ab:2c54:6fe5:d67] | 80, 443, 8080 | 0 |
| [2606:4700:2:695e:753c:a6c2:3c14:1fe9] | 80, 443, 8080 | 1 |
| [2606:4700:90d7:b752:4307:7f06:3e6:b644] | 80, 443, 8080 | 1 |
| [2606:4700:99e7:1a13:f3f4:91df:b805:9b6b] | 80, 443, 8080 | 1 |
| [2606:4700:2:695e:753c:a6c2:3c14:1fe9] | 80, 443, 8080 | 1 |
| [2606:4700:90d7:b752:4307:7f06:3e6:b644] | 80, 443, 8080 | 1 |
| [2606:4700:99e7:1a13:f3f4:91df:b805:9b6b] | 80, 443, 8080 | 1 |
| [2606:4700:2:695e:753c:a6c2:3c14:1fe9] | 80, 443, 8080 | 1 |
| [2606:4700:90d7:b752:4307:7f06:3e6:b644] | 80, 443, 8080 | 1 |
| [2606:4700:99e7:1a13:f3f4:91df:b805:9b6b] | 80, 443, 8080 | 1 |

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
