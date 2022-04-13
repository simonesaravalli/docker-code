# Build and execution instructions

docker build -t node_send_logs_to_cloudwatch .
docker run -p 49160:3000 -d node_send_logs_to_cloudwatch
