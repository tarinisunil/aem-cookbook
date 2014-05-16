# aem-cookbook

TODO: Finish the cookbook description.

## Supported Platforms

* CentOS

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['aem']['version']</tt></td>
    <td>String</td>
    <td>AEM version</td>
    <td><tt>nil</tt></td>
  </tr>
  <tr>
    <td><tt>['aem']['download_url']</tt></td>
    <td>String</td>
    <td>URL to AEM jar file</td>
    <td><tt>nil</tt></td>
  </tr>
  <tr>
    <td><tt>['aem']['license_url']</tt></td>
    <td>String</td>
    <td>URL to AEM license file</td>
    <td><tt>nil</tt></td>
  </tr>
</table>

## Usage

### aem::author

Include `aem::author` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[aem::author]"
  ]
}
```

### aem::publish

Include `aem::publish` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[aem::publish]"
  ]
}
```

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (i.e. `add-new-recipe`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request

## License and Authors

- Author:: Bryce Lynn (<bryce@tacitknowledge.com>)
- Author:: Alex Dunn (<adunn@tacitknowledge.com>)
- Author:: Paul Dunnavant (<pdunnavant@tacitknowledge.com>)

```text
Copyright 2012-2014, Tacit Knowledge, Inc.

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