# Elasticsearch Dockerfile for AWS

This image simply adds the [AWS Cloud Plugin](https://github.com/elastic/elasticsearch-cloud-aws) to the [offical Elasticsearch docker image](https://hub.docker.com/_/elasticsearch). Nothing more, nothing less.

## Plugin Installed

| Name | Default Version | Environment Variable |
|------|-----------------|----------------------|
| [AWS Cloud](https://github.com/elastic/elasticsearch-cloud-aws) | `2.7.1` | `CLOUD_AWS_VERSION` |

## Contributing

1. Fork it
2. Checkout the develop branch (`git checkout -b develop`)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request

## License

This application is distributed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
