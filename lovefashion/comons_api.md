# 爱时尚精品屋App公共接口
------------

查询商品列表接口

* url:  https://www.simoniu.com/commons/items/catalog/pager/%E6%9C%8D%E9%A5%B0/1
* method: GET

[查询商品列表接口](https://www.simoniu.com/commons/items/catalog/pager/%E6%9C%8D%E9%A5%B0/1)


微信支付接口

* url:   https://www.simoniu.com/commons/pay/weixin/cashier
* method:  POST
* data:

{
    "oid": "2022041221340816497704484398e6dcdb155914925aeb2fed46e1cb552",
    "uid": "22",
    "realname": "南阳理工软件学院",
    "mobile": "18991167123",
    "totalPrice": "0.01"
}

[微信支付接口](https://www.simoniu.com/commons/pay/weixin/cashier)


微信支付二维码生成接口

* url: https://www.simoniu.com/commons/pay/weixin/qrcode
* method: POST
* data:

{
    "oid": "2022041221340816497704484398e6dcdb155914925aeb2fed46e1cb552",
    "uid": "22",
    "realname": "南阳理工软件学院",
    "mobile": "18991167123",
    "totalPrice": "0.01"
}

[微信支付二维码生成接口](https://www.simoniu.com/commons/pay/weixin/qrcode)