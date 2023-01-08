# AWS lambda layer: python `fonttools`

### How to use it

1. Build needed image:
```sh
docker build -t aws_lambda_builder_image .
```

2. Run the runner script
```sh
./runner.sh
```

3. Upload the `.zip` as lambda layer


_Reference example: https://www.youtube.com/watch?v=jXjMrWCpaI8_ 