# exid
`exid` is short for **Exchangeable Identifiers**, providing a uniform representation
of identifiers which can be shared accross resource providers.
It is designed as the following format:
```text
exid://TYPE/IDENTIFIER?PARAMETERS
```

# Examples

```text
# Auth related identifiers.
exid://appid/13708001?issuer=dingtalk
exid://openid/ou_5f1123de598ff9a29cba5ffd798c6dbd?issuer=lark
exid://unionid/pzyngsulJFCZ2z1aYeS8h-nuasde8g?issuer=wechat
exid://userid/018f66bb-244b-71c2-9bdd-736afbe5a6c6?format=uuid&version=7

# Standard ID formats.
exid://mongodb-oid/507f191e810c19729de860ea
exid://snowflake-id/1541815603606036480
exid://sqids/Lqj8a0
exid://uuid/67e55044-10b1-426f-9247-bb680e5fe0c8
```
