# ec2

Link Followed : <https://medium.com/@junseopark/from-zero-to-aws-ec2-for-data-science-62e7a22d4579>
Connecting:

```bash
sudo ssh -i ./stocks-health.pem ec2-user@ec2-13-233-112-208.ap-south-1.compute.amazonaws.com
```

Sending File:

```bash
sudo scp -i ./stocks-health.pem <file-path> ec2-user@ec2-13-233-112-208.ap-south-1.compute.amazonaws.com:~/test
```

Hit it on: <http://ec2-13-233-112-208.ap-south-1.compute.amazonaws.com:8000/>
