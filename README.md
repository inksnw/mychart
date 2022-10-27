# helm-chart

## [使用方法](https://inksnw.github.io/mychart)

1、添加chart仓库

```
$ helm repo add myrepo https://inksnw.github.io/mychart
```

2、添加成功

```bash
$ helm repo list
NAME  	URL                                   
myrepo	https://inksnw.github.io/mychart
```

3、搜索chart包

```bash
$ helm search repo myrepo -l
NAME                              	CHART VERSION	APP VERSION	DESCRIPTION                                   
myrepo/test                       	0.1.0        	0.1.0     	A Helm chart for Kubernetes 
```

4、安装chart包
```bash
$ helm install xxx myrepo/test
```

xxx为relaese名字
