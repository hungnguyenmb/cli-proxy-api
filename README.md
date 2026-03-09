# 🚀 CLI Proxy API Setup

Dự án này giúp đóng gói các mô hình AI từ CLI (Gemini, Claude, Codex) thành OpenAI-compatible API.

## 🛠️ Cấu hình nhanh
1. Coppy file cấu hình: `cp cliproxy/config.yaml.example cliproxy/config.yaml`
2. Chạy Docker: `docker compose up -d`
3. Đăng nhập tài khoản AI:
   ```bash
   docker exec -it cli-proxy-api /CLIProxyAPI/CLIProxyAPI --login --no-browser
   ```

## 📡 API Endpoints
- Base URL: `http://<vps-ip>:8317/v1`
- API Key: Xem trong `config.yaml`

---
*Dự án được khởi tạo tự động bởi Antigravity Agent.*
