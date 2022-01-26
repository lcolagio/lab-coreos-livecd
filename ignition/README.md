

# Install butane

```
curl https://mirror.openshift.com/pub/openshift-v4/clients/butane/latest/butane --output butane
chmod +x butane
echo $PATH
```

# Transform butane to ignition

```
./butane 98-var-partition-etcd.bu -o openshift/98-var-partition-etcd.yaml
```



