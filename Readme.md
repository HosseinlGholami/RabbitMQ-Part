to access rabbitmqctl inside docker :
docker exec <NAME OF SERVICE> rabbitmqctl <COMMAND>
example:
        docker exec rabbitHGH rabbitmqctl status
        docker exec rabbitHGH rabbitmqctl list_queues
        docker exec rabbitmqctl list_queues name messages_ready messages_unacknowledged //for debuge wich messages arent ACK