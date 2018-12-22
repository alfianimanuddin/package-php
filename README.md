# package-php
Latihan Package PHP

requirements:
1. github
2. packagist.org
3. nama vendor/name harus sama dengan github

1. composer init
2. bikin file baru .php (bebas)
3. edit composer.json, tambahkan :
    "autoload": {
          "files": [
              "Hello.php"
          ]
      }
      
4. membuat version dari package yg kita buat
5. git tag 1.0 -m "package first version" (git tag [version-name] -m "your description")
6. git tag -l (check status)
7. git push origin 1.0 (git push origin [version-name])
