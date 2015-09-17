# Elasticsearch Dockerfile for AWS

This is an Elasticsearch [docker](https://www.docker.com) image bundled with a handful plugins to ease deployment to AWS. The image uses the [offical Elasticsearch image](https://hub.docker.com/_/elasticsearch).

## Plugins Installed

| Name | Default Version | Environment Variable |
|------|-----------------|----------------------|
| [AWS Cloud](https://github.com/elastic/elasticsearch-cloud-aws) | `2.7.1` | `CLOUD_AWS_VERSION` |
| [Head](https://github.com/mobz/elasticsearch-head) | - | - |

## Contributing

1. Fork it
2. Checkout the develop branch (`git checkout -b develop`)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request

## License

This application is distributed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
