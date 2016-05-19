# docker-ebs-persistence
Use this lightweight docker to guarantee EBS persistence

### Example usage

```
docker pull pebbletech/docker-ebs-persistence
docker run pebbletech/docker-ebs-persistence python attach_volume.py --tag Name --value asg --attach_as /dev/sdf
```
