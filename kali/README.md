# 🐋 Kali Linux Docker - Security Tools

## 🚀 Quick Start

### Build & Run
```bash
cd kali
docker-compose build
docker-compose up -d
docker exec -it my-kali-security /bin/bash
```

### Run Single Command
```bash
docker run --rm -it kalilinux/kali-rolling nmap -V
```

## 🔧 Tools Included

| Tool | Purpose |
|------|---------|
| nmap | Network scanner |
| metasploit-framework | Penetration testing |
| burpsuite | Web vulnerability scanner |
| sqlmap | SQL injection tool |
| nikto | Web server scanner |
| hydra | Password cracking |
| john | Password cracker |
| hashcat | GPU password cracking |
| net-tools | Network utilities |
| tcpdump | Packet analyzer |

## ⚠️ Disclaimer

**CHỈ SỬ DỤNG CHO MỤC ĐÍCH HỌC TẬP & SECURITY TESTING TRÊN MÁY CỦA BẠN!**

- ✅ Scan ports trên máy mình
- ✅ Test security của website mình
- ✅ Học cách tools hoạt động
- ❌ Không hack máy người khác
- ❌ Không crack WiFi người khác
- ❌ Không tấn công server không phải của bạn

## 🧪 Test Security Của Mình

```bash
# Scan máy mình
nmap -sV localhost

# Check open ports
nmap -sT localhost

# Test website của mình
nikto -h http://localhost

# SQL injection test (trên site của bạn)
sqlmap -u "http://yoursite.com/page?id=1"
```

## 📁 Workspace

Mount thư mục workspace để lưu results:
```bash
# Access from Kali
cd /workspace
```
