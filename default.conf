server {
  index index.html;
  server_name blog.withflare.io;
  rewrite ^/$ /index.html permanent;
  location / {
    root /usr/share/nginx/www/static/blog;
  }
}