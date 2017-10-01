FROM fluent/fluentd:v0.12

RUN fluent-gem install fluent-plugin-elasticsearch

RUN fluent-gem install fluent-plugin-splunkhec

ADD etc/fluent.conf /fluentd/etc/fluent.conf
