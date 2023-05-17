# GitHub Action for Continuous Profiling

GitHub Action for Continuous Profiling which you can run to profile your CI/CD. It uses parca and Polar Signals cloud.

## How to use

You will need access to Polar Signals cloud or another way to parca profiles to remote store. 

This project is also a demo of how to use this action, view the .github/workflows dir to view the example yaml.

If you are using Polar Signals cloud, the only thing required to configure is the `ps_token` which is the API token for Polar Signals cloud, where it sends the profiling data. You can view the docs on that [here](https://www.polarsignals.com/docs/generating-tokens).

Profiling data from one CI run looks [like this](https://pprof.me/475d1cc/).
