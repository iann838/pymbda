# Pymbda

Simple lightweight CLI for deploying AWS Lambda functions and layers.

```sh
pip install pymbda
```

Requires `aws.cfg` file with AWS credentials on root directory.

```toml
[default]
region = us-east-1
aws_access_key_id = ***
aws_secret_access_key = ***
```

# Usage
```
usage: pymbda [resouce] [command] ...

resources:
  functions     AWS Lambda Functions
    init [folder_name]
    build [folder_name]
    deploy [folder_name]
    publish [folder_name]
    alias [folder_name] [alias_name] [version]

  layers        AWS Lambda Layers
    init [folder_name]
    build [folder_name]
    deploy [folder_name]
```
