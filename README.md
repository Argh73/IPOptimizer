# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-06 17:00:32 +0330

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
| 198.41.209.144 | 80, 443, 8080 | 54 |
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 172.67.162.75 | 80, 443, 8080 | 134 |
| 172.67.171.230 | 80, 443, 8080 | 135 |
| 172.67.155.83 | 80, 443, 8080 | 135 |
| 172.67.73.87 | 80, 443, 8080 | 138 |
| 104.18.75.40 | 80, 443, 8080 | 141 |
| 104.17.205.62 | 80, 443, 8080 | 143 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.17.241.182 | 80, 443, 8080 | 148 |
| 104.16.177.11 | 80, 443, 8080 | 149 |
| 104.17.17.28 | 80, 443, 8080 | 149 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:440e:6c8d:c2c3:f1a3:c2c0:dd70] | 80, 443, 8080 | 3 |
| [2606:4700:3019:6cf7:acbb:2e8f:ddf4:2d13] | 80, 443, 8080 | 3 |
| [2606:4700:3013:16d7:4cc1:a16e:284:b49c] | 80, 443, 8080 | 3 |
| [2606:4700:440e:6c8d:c2c3:f1a3:c2c0:dd70] | 80, 443, 8080 | 3 |
| [2606:4700:3019:6cf7:acbb:2e8f:ddf4:2d13] | 80, 443, 8080 | 3 |
| [2606:4700:3013:16d7:4cc1:a16e:284:b49c] | 80, 443, 8080 | 3 |
| [2606:4700:440e:6c8d:c2c3:f1a3:c2c0:dd70] | 80, 443, 8080 | 3 |
| [2606:4700:3019:6cf7:acbb:2e8f:ddf4:2d13] | 80, 443, 8080 | 3 |
| [2606:4700:3013:16d7:4cc1:a16e:284:b49c] | 80, 443, 8080 | 3 |
| [2606:4700:440e:d253:6ef8:762c:9bd9:f36] | 80, 443, 8080 | 12 |
| [2606:4700:440e:d253:6ef8:762c:9bd9:f36] | 80, 443, 8080 | 12 |
| [2606:4700:440e:d253:6ef8:762c:9bd9:f36] | 80, 443, 8080 | 12 |
| [2606:4700:3019:9a3e:5aca:a3ed:1ab6:fa8f] | 80, 443, 8080 | 14 |
| [2606:4700:3019:9a3e:5aca:a3ed:1ab6:fa8f] | 80, 443, 8080 | 14 |
| [2606:4700:3019:9a3e:5aca:a3ed:1ab6:fa8f] | 80, 443, 8080 | 14 |

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
