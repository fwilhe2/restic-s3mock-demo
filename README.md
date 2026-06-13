Demo for using restic with s3 api.

```
docker exec -it restic-client restic backup /data

docker exec -it restic-client restic snapshots

docker exec -it restic-client restic stats
```
