FROM rabbitmq:3.7-management

ENV RABBITMQ_DEFAULT_USER admin
ENV RABBITMQ_DEFAULT_PASS admin

RUN rabbitmq-plugins enable --offline rabbitmq_mqtt 
RUN rabbitmq-plugins enable --offline rabbitmq_management 

# RUN rabbitmqctl set_permissions -p / admin ".*" ".*" ".*" 

