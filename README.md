# dockerimage-nginx-rtmp
lightweight rtmp &amp; HLS server

轻量级流媒体服务器

## Usage
`docker run -p 1935:1935 -p 80:80 registry.cn-shanghai.aliyuncs.com/alfredg/nginx-rtmp`

If you want to use a custom nginx.conf file or webpage files, create a volume mapping:

`docker run -dp 1935:1935 -p 80:80 -v /path/to/my/custom/nginx.conf:/etc/nginx/nginx.conf -v /path/to/wwwroot:/var/www registry.cn-shanghai.aliyuncs.com/alfredg/nginx-rtmp`

