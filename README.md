# install-docker playbook

## Scope

This is a automated way to install docker on supported VMs.

## Usage

**Note**: Be sure you can login via `root` otherwise you're not gonna get very far.

```bash
ansible-playbook -i hosts -u root -k playbook/main.yaml
```

## Tested on

This has been tested and works on:
- Debian 10

## License & Authors

If you would like to see the detailed LICENSE click [here](./LICENSE).

- Author: JJ Asghar <awesome@ibm.com>

```text
Copyright:: 2021- IBM, Inc

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
