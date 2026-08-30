# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-08-30 15:37:58 +0330

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
| 104.18.66.17 | 80, 443, 8080 | 141 |
| 104.18.66.17 | 80, 443, 8080 | 141 |
| 104.18.66.17 | 80, 443, 8080 | 141 |
| 104.16.166.115 | 80, 443, 8080 | 143 |
| 104.19.118.30 | 80, 443, 8080 | 143 |
| 104.16.166.115 | 80, 443, 8080 | 143 |
| 104.19.118.30 | 80, 443, 8080 | 143 |
| 104.16.166.115 | 80, 443, 8080 | 143 |
| 104.19.118.30 | 80, 443, 8080 | 143 |
| 104.18.6.128 | 80, 443, 8080 | 149 |
| 104.18.6.128 | 80, 443, 8080 | 149 |
| 104.18.6.128 | 80, 443, 8080 | 149 |
| 104.19.74.134 | 80, 443, 8080 | 150 |
| 104.19.74.134 | 80, 443, 8080 | 150 |
| 104.19.74.134 | 80, 443, 8080 | 150 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:9b06:69e4:f574:668e:219:fc5a] | 80, 443, 8080 | 0 |
| [2606:4700:8d9c:b2e0:5ad6:f0de:1ba2:43a5] | 80, 443, 8080 | 0 |
| [2606:4700:9b06:69e4:f574:668e:219:fc5a] | 80, 443, 8080 | 0 |
| [2606:4700:8d9c:b2e0:5ad6:f0de:1ba2:43a5] | 80, 443, 8080 | 0 |
| [2606:4700:9b06:69e4:f574:668e:219:fc5a] | 80, 443, 8080 | 0 |
| [2606:4700:8d9c:b2e0:5ad6:f0de:1ba2:43a5] | 80, 443, 8080 | 0 |
| [2606:4700:9c60:f754:2687:eae0:5d9d:d368] | 80, 443, 8080 | 1 |
| [2606:4700:9c60:d925:80dd:844:58da:c6b6] | 80, 443, 8080 | 1 |
| [2606:4700:9c60:f754:2687:eae0:5d9d:d368] | 80, 443, 8080 | 1 |
| [2606:4700:9c60:d925:80dd:844:58da:c6b6] | 80, 443, 8080 | 1 |
| [2606:4700:9c60:f754:2687:eae0:5d9d:d368] | 80, 443, 8080 | 1 |
| [2606:4700:9c60:d925:80dd:844:58da:c6b6] | 80, 443, 8080 | 1 |
| [2606:4700:90d2:a15e:6dc3:2f4f:7f46:ec8c] | 80, 443, 8080 | 3 |
| [2606:4700:90d2:a15e:6dc3:2f4f:7f46:ec8c] | 80, 443, 8080 | 3 |
| [2606:4700:90d2:a15e:6dc3:2f4f:7f46:ec8c] | 80, 443, 8080 | 3 |

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
