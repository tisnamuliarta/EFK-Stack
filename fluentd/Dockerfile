FROM fluent/fluentd:v1.14-1

USER root

# Use root account to install plugins
RUN gem install fluent-plugin-elasticsearch --no-document

USER fluent

