## 初期化
```
Router# configure
Router(config)# erase startup-config
Are you sure you want to erase the startup-configuration? (Yes or [No]): y
Router(config)# exit
Router# default-console command-line
Router# reload
```

## 設定確認
```
Router# configure
Router(config)# show config
```

## ip確認
```
Router# configure
Router(config)# show ip address
```


## 保存
```
Router(config)# write memory
```