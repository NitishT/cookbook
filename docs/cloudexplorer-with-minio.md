# How to use Cloud Explorer with MinIO [![Slack](https://slack.min.io/slack?type=svg)](https://slack.min.io)

In this recipe you will learn how to carry out basic operations on MinIO using Cloud Explorer.Cloud Explorer is a open-source S3 client. It works on Windows, Linux, and Mac. It has a graphical and command line interface for each supported operating system. If you have a feature suggestion or find a bug, please open an issue.

## Features

* Search
* Performance testing
* Migrate buckets between S3 accounts
* Simple text editor
* Sync folders
* Create snapshots of buckets

## Prerequisites

- [Cloud Explorer](https://github.com/rusher81572/cloudExplorer) is installed and running.

- MinIO Server is running on localhost on port 9000 in `HTTP`, follow [MinIO quickstart guide](https://docs.min.io/docs/minio-quickstart-guide) to install MinIO.


## Steps

- Add your MinIO account to Cloud Explorer and click save.

![ACCOUNT](https://raw.githubusercontent.com/minio/cookbook/master/docs/screenshots/cloudexplorer/cloudexplorer-1.png)

- Click on the MinIO account and then the "Load" button to connect. In the future, clicking on a saved S3 account will automatically load the account and show the buckets.

![ACCOUNT](https://raw.githubusercontent.com/minio/cookbook/master/docs/screenshots/cloudexplorer/cloudexplorer-2.png)

- Create a bucket

![B_LISTING](https://raw.githubusercontent.com/minio/cookbook/master/docs/screenshots/cloudexplorer/cloudexplorer-3.png)

- Upload a file to a bucket

![D_BUCKET](https://raw.githubusercontent.com/minio/cookbook/master/docs/screenshots/cloudexplorer/cloudexplorer-4.png)

- Click on the Magifing glass and then click "Refresh Bucket" to view the uploaded file

![D_BUCKET](https://raw.githubusercontent.com/minio/cookbook/master/docs/screenshots/cloudexplorer/cloudexplorer-6.png)


## Explore Further

- [MinIO Client complete guide](https://docs.min.io/docs/minio-client-complete-guide)
- [Cloud Explorer homepage](https://github.com/rusher81572/cloudExplorer)
- [Linux-toys.com](https://www.linux-toys.com/?page_id=211)
