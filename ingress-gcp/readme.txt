add services ,remove nodeport and add clsuter ip
before applying ingree apply secrets from auth

All above notes for ingress 
1)Create cluster and make all service as clusterIP
2)create a secret auth and make sure you enter password in base64 from http://www.htaccesstools.com/htpasswd-generator/
3)Go to this page to start ingress ,2 files that needs to be applied ,mandatory and nginx ,which will place a load balncer in fron of ingress.
https://kubernetes.github.io/ingress-nginx/deploy/
4) Create authenticatio  https://kubernetes.github.io/ingress-nginx/examples/auth/basic/
5) Apply ingress publiic and secure files 
6) Make entry in /etc/hosts files to point to yupur domain name 
7) See it in action
