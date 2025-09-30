## Steps

1. Spin up the Kafka cluster and its containers by running the `setup.sh` script.
2. Open a shell terminal inside the Kafka container using:
   ```bash
   docker exec --workdir /opt/kafka/bin/ -it <container-id> sh

3. You can get the container ID by running:

   ```bash
   docker container ls
   ```

