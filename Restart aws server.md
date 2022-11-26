Steps here:

              copy and paste this in terminal

              sudo systemctl restart gunicorn

              sudo systemctl daemon-reload

              sudo systemctl restart gunicorn.socket gunicorn.service

              sudo nginx -t && sudo systemctl restart nginx
