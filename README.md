# Hyeong Joon Suh Personal Website
## Deploy changes
```bash
# Configure AWS credentials for authentication. Need access key ID and secret access key, created in IAM
aws configure

# At the root of repository
aws s3 sync . s3://hyeongjoonsuh.com --delete
```

## Run website on local server
```bash
# Website available at http://localhost:8000
python3 -m http.server 8000
```

## Copyright and License

Copyright 2013-2018 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-resume/blob/gh-pages/LICENSE) license.
