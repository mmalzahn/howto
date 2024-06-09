## config apt to use the apt-chache-ng instance as a proxy

#### add following line to the apt config:

```
Acquire::http::Proxy "http://<apt-cache-ng-ip>:<port>";
```


#### how to do it in terraform:

```hcl
  provisioner "file" {
    when        = create
    content     = "Acquire::http::Proxy \"http://10.123.100.4:3142\";"
    destination = "/etc/apt/apt.conf.d/01Proxyconfig"
  }
```

