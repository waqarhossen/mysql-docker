# MySQL Docker Setup

## Quick Start
1. Update passwords in docker-compose.yml
2. Run: `docker-compose up -d`
3. Access phpMyAdmin at: http://your-server-ip:8080

## Configuration
- MySQL Port: 3306
- phpMyAdmin Port: 8080
- Database: n8n_db
- User: n8n_user

## Domain Setup
Configure your domains:
- Main: auto.waqarh.com
- Database: db.auto.waqarh.com

## Security Notes
- Change all default passwords
- Use strong passwords
- Consider firewall rules for port 3306
