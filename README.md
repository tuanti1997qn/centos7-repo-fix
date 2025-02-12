# centos7-repo-fix

Replace /etc/yum.repo.d/CentOS-Base.repo

In case of certificate issue

```sudo vi /etc/yum.conf```

Add this to end of file

```sslverify=false```
