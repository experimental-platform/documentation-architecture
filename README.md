# Development

## Preparation

    git clone --recursive git@github.com:experimental-platform/experimental-platform.git

## Further Steps

Just follow your conscience, please.

# Obtaining IP Address

1. Connect monitor to device.
2. The IP Address will be displayed after the device finished booting.

# 3 Minute Use Case Examples

1. [node.js integration test](https://github.com/experimental-platform/test-integration-node.js/blob/master/run_tests.sh)
2. [Wordpress: currently out of order...](https://github.com/experimental-platform/test-integration-wordpress/blob/master/run_tests.sh)
3. [Python integration test](https://github.com/experimental-platform/test-integration-python/blob/master/run_tests.sh) 
4. [PHP integration test](https://github.com/experimental-platform/test-integration-php/blob/master/run_tests.sh)
5. [Rails integration test (WIP!)](https://github.com/experimental-platform/test-integration-rails/blob/master/run_tests.sh)


# Dokku-Debug Option

To debug your dokku deploy session simply add ```DOKKU_TRACE=1``` to your ssh key in ```.ssh/authorized_keys``` on server-side or set it through the shell.
