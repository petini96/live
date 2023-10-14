FROM confluentinc/cp-server:7.3.0

# Adicionando o comando ao arquivo de inicialização
RUN echo "kafka-topics --bootstrap-server=localhost:9092 --topic=product --create" >> /etc/confluent/docker/run

# Definindo o CMD como o script de inicialização padrão
CMD ["/etc/confluent/docker/run"]
