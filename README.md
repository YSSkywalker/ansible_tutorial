# Ansibleを使用してApacheを起動する
## Apacheをインストール、起動する
```
$ ansible-playbook -i inventory playbook.yml
```

## Apacheを停止する
```
$ brew services stop httpd 
```

## Apacheを再起動する
```
$ brew services restart httpd
```

## Apacheのステータスを確認する
```
$ brew services list
```