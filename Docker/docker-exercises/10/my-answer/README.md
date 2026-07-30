# AWS CLI with Dockerfile

You can call this image for run aws cli without install into yout computer.
Of course, you need a aws credentials to use:

```bash
# Example
docker run --rm -ti-v /.aws/:/root/.aws personal:v3 configure list
```


