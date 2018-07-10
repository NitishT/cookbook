# Minio Cookbook [![Slack](https://slack.minio.io/slack?type=svg)](https://slack.minio.io)

Minio Cookbook is the home for recipes that help you integrate Minio with your technology stack.

## Reverse Proxy and load-balancers

- [Setup Caddy proxy with Minio](./docs/setup-caddy-proxy-with-minio.md)
- [Setup Apache HTTP proxy with Minio](./docs/setup-apache-http-proxy-with-minio.md)
- [Setup Nginx proxy with Minio](./docs/setup-nginx-proxy-with-minio.md)
- [How to run multiple Minio servers with Nginx inside docker container](./docs/multiple-minio-servers-with-nginx-inside-docker-container.md)
- [How to run multiple Minio servers with Træfɪk](./docs/multiple-minio-servers-with-traefik.md)
- [How to run load-balanced distributed Minio in Docker swarm with Træfɪk](./docs/distributed-minio-with-traefik-as-loadbalancer-in-swarm.md)

## Database backup and snapshots

- [Store MongoDB Backups in Minio](./docs/store-mongodb-backups-in-minio.md)
- [Store MySQL Backups in Minio](./docs/store-mysql-backups-in-minio.md)
- [Store PostgreSQL Backups in Minio](./docs/store-postgresql-backups-in-minio.md)
- [Store Elasticsearch Snapshots on Minio](./docs/elasticsearch-snapshots-on-minio.md)
- [Aggregate Apache logs with fluentd and Minio](./docs/aggregate-apache-logs-with-fluentd-and-minio.md)
- [How to use Minio Server as Laravel Custom File Storage](./docs/how-to-use-minio-as-laravel-file-storage.md)

## Performant big data storage and analysis

- [How to use Apache Spark with Minio](./docs/apache-spark-with-minio.md)
- [Tensorflow with Minio](https://www.tensorflow.org/versions/master/deploy/s3)<sup>*</sup>
- [Alluxio with Minio](https://www.alluxio.org/docs/master/en/Configuring-Alluxio-with-Minio.html)<sup>*</sup>

## AWS client tools with Minio

- [AWS CLI with Minio](./docs/aws-cli-with-minio.md)
- [How to use AWS SDK for PHP with Minio Server](./docs/aws-sdk-for-php-with-minio.md)
- [How to use AWS SDK for Go with Minio Server](./docs/aws-sdk-for-go-with-minio.md)
- [How to use AWS SDK for Python with Minio Server](./docs/aws-sdk-for-python-with-minio.md)
- [How to use AWS SDK for Ruby with Minio Server](./docs/aws-sdk-for-ruby-with-minio.md)
- [How to use AWS SDK for Javascript with Minio Server](./docs/aws-sdk-for-javascript-with-minio.md)
- [How to use AWS SDK for DotNet with Minio Server](./docs/aws-sdk-for-dotnet-with-minio.md)
- [How to use AWS SDK for iOS with Minio Server](./docs/aws-sdk-for-iOS-with-minio.md)
- [How to use fog AWS for Ruby with Minio Server](./docs/fog-aws-for-ruby-with-minio.md)
- [S3cmd with Minio](./docs/s3cmd-with-minio.md)

## Encryption using AWS client tools

- [How to use Minio server-side-encryption with aws-cli](/docs/how-to-use-minio-server-side-encryption-with-aws-cli.md)
- [How to use AWS SDK for Java for client-side-encryption with Minio Server](./docs/how-to-use-aws-sdk-java-encryption.md)

## Presigned operations

- [Download from Browser with PreSignedGet](./docs/presigned-get-download-from-browser.md)
- [Upload via Browser with PreSignedPut](./docs/presigned-put-upload-via-browser.md)

## Desktop backup to Minio

- [restic with Minio](https://restic.readthedocs.io/en/stable/030_preparing_a_new_repo.html#minio-server)<sup>*</sup>
- [Rclone with Minio](https://rclone.org/s3/#minio)<sup>*</sup>
- [Arq with Minio](https://www.arqbackup.com/documentation/pages/strategy.html)<sup>*</sup>
- [How to use Cyberduck with Minio](https://cyberduck.io/s3/)<sup>*</sup>

## Storage backends

- [Running Minio in FreeNAS](./docs/running-minio-in-freenas.md)
- [How to use s3fs-fuse with Minio](./docs/s3fs-fuse-with-minio.md)

## Generic resources

- [How to install Golang](./docs/how-to-install-golang.md)
- [Generate Let's Encrypt certificate using Certbot for Minio](./docs/generate-lets-encypt-certificate-using-certbot-for-minio.md)

Note that items marked <sup>*</sup> indicate an external link.