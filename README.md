# rails-docker-template

original content [https://qiita.com/reflet/items/f73cac406760ee4ecc13](https://qiita.com/reflet/items/f73cac406760ee4ecc13)

# how to set up rails project 

1. clone this repo or make new repo with using this repo as the template
2. run `docker-compose build`
3. run `docker-compose run rails rails new . --force --database=mysql --skip-bundle`
4. update database setting same as [this](https://qiita.com/reflet/items/f73cac406760ee4ecc13#%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9%E8%A8%AD%E5%AE%9A%E3%82%92%E4%BF%AE%E6%AD%A3)
5. uncomment the last 2 line2 of `Dockerfile`
6. re run `docker-compose build`
7. run `docker-compose up -d`

http://localhost
