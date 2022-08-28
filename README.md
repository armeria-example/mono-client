# interface repository setting
[mono-interface link](https://github.com/armeria-example/mono-interface)

### add interface repository
```
git submodule add https://github.com/armeria-example/mono-idl
```

### pull interface repository
```
cd mono-interface
git pull origin main
./gradlew generateProto
```

# test

### client test
```
curl -XPOST -H 'content-type: application/json; charset=utf-8' http://127.0.0.1:8080/api/v1/user
```

# info
- [idl](https://github.com/armeria-example/mono-idl)
- [server](https://github.com/armeria-example/mono-server)
- [client](https://github.com/armeria-example/mono-client)