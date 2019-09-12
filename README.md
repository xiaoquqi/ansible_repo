## How to use script?

### Update inventory

Use nested style to define host resource.

### How to run?


#### Use root user

```
ansible-playbook k8s.yml -i inventory -t init
```


#### Use sudo

-b, --become        run operations with become (does not imply password prompting)

```
ansible-playbook k8s.yml -i inventory -t init -b
```
