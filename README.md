# Friends App

```shell
$ rails _7.0.4_ new friends_app
```

```shell
$ rails g scaffold friends first_name last_name email phone twitter facebook instagram
```

```shell
$ bundle add devise
```

```shell
$ rails g devise:install
```

```shell
$ rails g devise User
```

```shell
$ rails g migration add_user_id_to_friends user_id:integer:index
```

```shell
$ rails db:migrate
```


