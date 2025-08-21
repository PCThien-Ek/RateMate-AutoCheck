# Auto-Check-Web

## Yêu cầu
- Docker + Make

## Cách chạy local
```bash
cp .env.example .env   # sửa thông số phù hợp môi trường
make build             # build image Docker
make run               # chạy full suite (không dùng cache browser)
# hoặc
make smoke             # chạy nhanh
