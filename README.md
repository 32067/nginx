# Sample Nginx application for Swarm/Kubernetes Deployments

## Update welcome page

更新欢迎页面

```html
<h1>Welcome to nginx!</h1>
<p>If you see this page, the nginx web server is successfully installed and
working. Further configuration is required.</p>
```

## git commmit

```
git add .
git commit -m "updates"
git push
```

## Deploy to Swarm cluster

把docker-compose.yml中的(dtr)和(tag)变量替换为实际的值，然后部署

## Deploy to Kubernetes cluster

把nginx-deployment.yml中的(dtr)和(tag)变量替换为实际的值，然后部署
nginx-svc.yml用来部署一个服务
