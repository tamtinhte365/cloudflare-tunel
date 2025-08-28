1. đăng nhập cloudflare, vào networks/tunnels

2. Ấn create a tunel, rồi chọn docker

3. Chỉ copy mình mã token rồi thay vào đoạn code dưới đây:

docker run -d --name cloudflared --restart unless-stopped --network host cloudflare/cloudflared:latest tunnel --no-autoupdate run --token eyJhIjoiZGQ3MmM3ZjBjMzQyZGM4M2Y4ZjA1ZjNlYWE5NDYyODciLCJ0IjoiMDU1ZDA1MzYtOTc0YS00NzFlLTkzMDItMWI4NGU4NDgyZTg4IiwicyI6Ik5tRm1ZemRpWkRFdE5qSTFNeTAwTmprNUxUa3pNemt


4. Paste vào teminal là done. bao mượt
