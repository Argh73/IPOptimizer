# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-19 02:00:55 +0330

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
| 198.41.208.173 | 80, 443, 8080 | 51 |
| 198.41.208.170 | 80, 443, 8080 | 51 |
| 198.41.208.173 | 80, 443, 8080 | 51 |
| 198.41.208.170 | 80, 443, 8080 | 51 |
| 198.41.209.140 | 80, 443, 8080 | 52 |
| 198.41.209.140 | 80, 443, 8080 | 52 |
| 198.41.211.184 | 80, 443, 8080 | 64 |
| 172.67.159.75 | 80, 443, 8080 | 95 |
| 172.67.159.75 | 80, 443, 8080 | 95 |
| 172.67.156.48 | 80, 443, 8080 | 96 |
| 172.67.156.48 | 80, 443, 8080 | 96 |
| 104.17.240.48 | 80, 443, 8080 | 138 |
| 104.17.167.246 | 80, 443, 8080 | 138 |
| 172.64.88.185 | 80, 443, 8080 | 138 |
| 104.19.16.179 | 80, 443, 8080 | 138 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9add:182a:2d09:5e46:733e:9a1c] | 80, 443, 8080 | 3 |
| [2606:4700:9add:2f06:6549:2586:6c99:de86] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:a894:cfbf:4205:9b89:a18c] | 80, 443, 8080 | 3 |
| [2606:4700:90d1:fbfa:9f5:464e:eff1:31e7] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:109b:4755:74c4:88b5:6284] | 80, 443, 8080 | 3 |
| [2606:4700:9add:182a:2d09:5e46:733e:9a1c] | 80, 443, 8080 | 3 |
| [2606:4700:9add:2f06:6549:2586:6c99:de86] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:a894:cfbf:4205:9b89:a18c] | 80, 443, 8080 | 3 |
| [2606:4700:90d1:fbfa:9f5:464e:eff1:31e7] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:109b:4755:74c4:88b5:6284] | 80, 443, 8080 | 3 |
| [2606:4700:9add:182a:2d09:5e46:733e:9a1c] | 80, 443, 8080 | 3 |
| [2606:4700:9add:2f06:6549:2586:6c99:de86] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:a894:cfbf:4205:9b89:a18c] | 80, 443, 8080 | 3 |
| [2606:4700:90d1:fbfa:9f5:464e:eff1:31e7] | 80, 443, 8080 | 3 |
| [2606:4700:90d5:109b:4755:74c4:88b5:6284] | 80, 443, 8080 | 3 |

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
