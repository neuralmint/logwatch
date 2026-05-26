<h1 align="center">📋 logwatch</h1>
<p align="center">
  <b>Real-time log monitoring and analysis from your terminal.</b>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/python-3.6+-blue.svg">
  <img src="https://img.shields.io/badge/dependencies-zero-brightgreen.svg">
  <img src="https://img.shields.io/badge/license-MIT-green.svg">
</p>

## 🚀 Install

```bash
curl -L https://raw.githubusercontent.com/neuralmint/logwatch/main/logwatch -o /usr/local/bin/logwatch
chmod +x /usr/local/bin/logwatch
```

## 📋 Commands

| Command | Description |
|---------|-------------|
| `logwatch tail <file>` | Follow log in real-time |
| `logwatch grep <file> <pat>` | Search with pattern |
| `logwatch levels <file>` | Count log levels (INFO/WARN/ERROR) |
| `logwatch ip <file>` | Extract & count IPs |
| `logwatch hh <file>` | Requests per hour |
| `logwatch codes <file>` | HTTP status code distribution |
| `logwatch json <file>` | Extract JSON from logs |
| `logwatch sample <file> [n]` | Sample N random lines |

## 💝 Donate

**BTC:** `bc1q6ud0w3036ye2vfzkftwywarqswqu3jehs4nqe7`
