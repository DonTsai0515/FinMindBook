# FinMindBook 總結

## 
1. 為了解決金融數據問題，開發爬蟲、自動化收集資料
2. 證交所遇到封鎖 IP 問題，接觸 RabbitMQ、Flower、Celery 分散到多台機器
3. 資料存放問題，架設 MySQL 
4. 多個服務要部署到多台機器上，開始使用 Docker 架設服務，順便解決部署及更新問題
5. 為了管理多個 Docker，利用 Docker Swarm 及 Portainer UI 管理機器
6. API 服務，方便串接獲取資料
7. No-IP 解決網址問題
8. Let's Encrypt 處理 SSL 相關安全性問題
9. API 使用 SSL 憑證，多數使用 Nginx，但是現代架構及容器技術改選用 Traefik

---
10. 應用資料面：視覺化工具 Redash 製作 Dashboard
