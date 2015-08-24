# Apache Spark Setup on LMFDB

1. Use `sbin/start-all.sh` to start the master on lmfdb and the workers as configured here and listed in `slaves`
2. Open ssh tunnels to 4040 and 8080 to see the status boards.
3. To confirm its working, run `./bin/spark-shell --master spark://192.168.13.2:7077` where the IP is `lmfdb-ib`.


