---
layout: post
title: Java'da Thread Dump Nasıl Alınır
date: 2022-08-02 01:33:20 +0300
description: Thread Dump
img: i-rest.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
categories: Java
tags: [Thread Dump, Deaclock]
---


Thread'lerin belirli bir zamandaki resmini çekip incelemenizi sağlar. Bu şekilde Thread'ler ile ilgili tüm bilgilere erişebiliriz. Problemleri görmemize, jvm ve uygulama peformansını artırmamıza imkan sağlar. Deadlock oluşumu varsa bunu da görmemizi sağlar. 


#### Kurulum

docker run -d -p 9000:9000 -p 9001:9001  --name myminio minio/minio:latest server /data --console-address ":9001"



log-bin=mysql-bin
expire_logs_days = 2
binlog_format=ROW