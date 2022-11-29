# Seabee Data Storage

Seabee's storage solution on [NIRD](https://www.sigma2.no/data-storage) is availiable for users through a S3-compatible API using [minio](https://min.io/). This allows users to access the storage endpoint, https://storage.seabee.sigma2.no, using any S3 compatible client. For example:

- [rclone](https://rclone.org/)
- [cyberduck](https://cyberduck.io)

In addition the storage, IAM and metrics can be accessed using the minio [console](https://min.io/docs/minio/linux/administration/minio-console.html) or the [client](https://min.io/docs/minio/linux/reference/minio-mc.html). There is also plans on providing a easy to use UI for sanitising uploads to some buckets.
