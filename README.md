# GoCD API Documentation

Checkout the live documentation at https://api.gocd.org

# Contributing to the API Documentation

### Configure and install middleman

```
$ bundle install
```

### Run the API documentation locally on http://localhost:4567

```
$ bundle exec middleman serve
```

### Generating the static website

```
$ bundle exec rake build
```

### Publish the website to Github Pages

```
$ bundle exec rake publish
```

## Need help?

* Just submit a issue to the [github repository](https://github.com/gocd/api.go.cd) if you need any help. And, of course, feel free to submit pull requests with bug fixes or changes.


## Special thanks

* [slate](https://github.com/tripit/slate)

## Contributing

We encourage you to contribute to Go. For information on contributing to this project, please see our [contributor's guide](https://www.gocd.org/contribute).
A lot of useful information like links to user documentation, design documentation, mailing lists etc. can be found in the [resources](https://www.gocd.org/community/resources.html) section.

## License

```plain
Copyright 2008-2013 Concur Technologies, Inc.
Copyright 2022 Thoughtworks, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
