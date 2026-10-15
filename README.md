# IPOptimizer

[![GitHub Actions](https://github.com/Argh94/IPOptimizer/workflows/IPOptimizer/badge.svg)](https://github.com/Argh94/IPOptimizer/actions)
[![PHP Version](https://img.shields.io/badge/PHP-8.0-blue)](https://www.php.net)
[![Update Frequency](https://img.shields.io/badge/Updates-Every%205%20Hours-green)](https://github.com/Argh94/IPOptimizer)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/Argh94/IPOptimizer)](https://github.com/Argh94/IPOptimizer/issues)

## 🚀 Network Optimization with Top IPs

**IPOptimizer** fetches a list of optimized IPs (IPv4 and IPv6) with the lowest latency from [Hostmonit](https://hostmonit.com/) every 5 hours. These IPs are ideal for configuring proxies, VPNs, or improving network performance.

**Last Updated:** 2026-10-15 15:25:43 +0330

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
| 162.159.236.194 | 80, 443, 8080 | 54 |
| 141.101.113.10 | 80, 443, 8080 | 55 |
| 172.64.67.117 | 80, 443, 8080 | 57 |
| 172.64.83.52 | 80, 443, 8080 | 57 |
| 198.41.208.251 | 80, 443, 8080 | 74 |
| 198.41.208.103 | 80, 443, 8080 | 90 |
| 198.41.208.202 | 80, 443, 8080 | 118 |
| 198.41.208.230 | 80, 443, 8080 | 142 |
| 172.67.251.117 | 80, 443, 8080 | 145 |
| 104.17.83.162 | 80, 443, 8080 | 147 |
| 104.16.201.189 | 80, 443, 8080 | 149 |
| 104.18.22.21 | 80, 443, 8080 | 149 |
| 104.19.30.238 | 80, 443, 8080 | 149 |
| 104.17.70.18 | 80, 443, 8080 | 155 |
| 162.159.251.4 | 80, 443, 8080 | 167 |

### IPv6
| IP | Suggested Ports | Latency (ms) |
|:---:|:---------------:|:------------:|
| [2606:4700:8dd2:494d:fde3:9256:3fd3:9891] | 80, 443, 8080 | 3 |
| [2606:4700:3006:649b:e823:9a15:aa4a:29eb] | 80, 443, 8080 | 3 |
| [2606:4700:440f:8fb1:79ef:bdb7:a0b7:bd41] | 80, 443, 8080 | 3 |
| [2606:4700:3006:3a6f:517f:7790:402d:73ed] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:494d:fde3:9256:3fd3:9891] | 80, 443, 8080 | 3 |
| [2606:4700:3006:649b:e823:9a15:aa4a:29eb] | 80, 443, 8080 | 3 |
| [2606:4700:440f:8fb1:79ef:bdb7:a0b7:bd41] | 80, 443, 8080 | 3 |
| [2606:4700:3006:3a6f:517f:7790:402d:73ed] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:494d:fde3:9256:3fd3:9891] | 80, 443, 8080 | 3 |
| [2606:4700:3006:649b:e823:9a15:aa4a:29eb] | 80, 443, 8080 | 3 |
| [2606:4700:440f:8fb1:79ef:bdb7:a0b7:bd41] | 80, 443, 8080 | 3 |
| [2606:4700:3006:3a6f:517f:7790:402d:73ed] | 80, 443, 8080 | 3 |
| [2606:4700:8dd2:fce2:ca3f:39b8:f9d9:761c] | 80, 443, 8080 | 4 |
| [2606:4700:8dd2:fce2:ca3f:39b8:f9d9:761c] | 80, 443, 8080 | 4 |
| [2606:4700:8dd2:fce2:ca3f:39b8:f9d9:761c] | 80, 443, 8080 | 4 |

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
