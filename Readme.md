接下来，添加一个 JDBC URL 模板，名称可以为任意（此处就叫“JDBC”），
模板为：jdbc:postgresql://{host}:{port}/{database}{user}{password}
这样做是因为，DataGrip 只会要求用户填写已经在模板中出现的参数，比如 {host}、{port}、{database}、{user}、{password}，
它会根据模板的情况智能生成一个对应的填写表，因此，DBeaver 的模板拿过来是不能使用的。后两个参数不会出现在 URL 当中，只作为引导 DataGrip 生成填写表使用。


jdbc:postgresql://{host}:{port}/{database}{user}{password}

jdbc:postgresql://192.168.0.14:8000/gaussdb

jdbc:gaussdb://192.168.0.14:8000/gaussdb
