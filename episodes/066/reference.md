-[ ][Vault: 基础教程之入门及使用介绍](https://blog.csdn.net/qq_34911465/article/details/81587922?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.nonecase&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.nonecase)
```
vault server -dev
# another terminal 
export VAULT_ADDR='http://127.0.0.1:8200'
vault status
# write
vault kv put secret/hello foo=world excited=yes
# read to check
vault kv get secret/hello
# or 
vault kv get -format=json secret/hello
# delete
vault kv delete secret/hello
```

-[ ] [使用vault管理Kubernetes Secret](https://www.jianshu.com/p/10bd4363e0f3)
```


```
