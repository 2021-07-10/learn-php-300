# Composer

|本期版本| 上期版本 
|:---:|:---:
`Sun Jun  5 00:04:03 CST 2022` | -

**依赖**

```bash
apt-get install php7.4-zip unzip
```

**安装**

```
curl -O https://mirrors.aliyun.com/composer/composer.phar
sudo mv composer.phar /usr/local/bin/composer
sudo chmod +x /usr/local/bin/composer
```

> `/etc/profile.d/composer.sh`

```
export PATH=$HOME/.config/composer/vendor/bin:$PATH
```

> 全局配置

```
composer config -g repo.packagist composer https://mirrors.aliyun.com/composer/
```

> 项目配置

```
composer config repo.packagist composer https://mirrors.aliyun.com/composer/
```


## Ref

* [https://getcomposer.org/](https://getcomposer.org/)
* [https://packagist.org/](https://packagist.org/)
* [Composer 中文网](https://www.phpcomposer.com/)
* [阿里云 Composer 全量镜像](https://developer.aliyun.com/composer)