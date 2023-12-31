## Introduction

This is an Open Source community project. Project contributors may be able to help, depending on their time and availability. Please be specific about what you're trying to do, your system, and steps to reproduce your scenario when opening a GitHub issue.

For bug reports, please [open an issue](https://github.com/trendmicro/tm-v1-containersecurity/issues/new)

> Note: Official support from Trend Micro is not available. Individual contributors may be Trend Micro employees but are not official support.

## For Contributors

We :heart: contributions from the community. To submit changes, please review the following information.

### Contributor Guidelines

Some tips before you start contributing to this project:

- The folder structure convention for this repo is '`/product-name/activity-name/{cloud-provider}-{language or framework}-your-script-foldername`'.

> For example, `/Integration/aws-cdk-workload-iam-stack`

**Note:** The `{cloud-provider}` is mandatory for the cases that it's applied, such as `aws-cdk-workload-iam-stack`. For others cases is not necessary, but use your best judgement before submit the PR.

- Recommended to create a README for your folder to make it easier for the community to make use of your script.
- Writing separate test scripts in the `/tests` folder or having a built-in `dry-run` mode in the script to ensure everyone can test your script in their environment is much appreciated :)
- Images and other assets are a welcome addition to your scripts to help everyone run tests / look at examples. Ensure they are stored in relevant folders beside your script, like `/img`, `/assets`, `/examples`, `/tests`. :warning: Avoid including logs with your submission unless it is used as an example. In that case, examples can be included in an `/examples` folder.
- Using language-specific linters is super beneficial for easier code reviews.
- For Python scripts, please consider submitting a `requirements.txt` file within your script folder for easier deployment. You can generate a requirements.txt file using the following command

``` bash
# Install and run in current directory

#  For Python 3:
pip3 install pipreqs
python3 -m  pipreqs.pipreqs .

#  For Python 2:
pip install pipreqs
python -m  pipreqs.pipreqs .

# To check your python version:
python --version
```

### Contribute

1.  Fork this repository.
2.  Create a new feature branch, preferably from the `main` branch.
3.  Commit your code with a message that is structured according to the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.
4.  Make your changes.
5.  Submit a pull request with an explanation for your changes or additions.

We will review and work with you to release the changes.

### Code of Conduct

Trend Micro has adopted a [Code of Conduct](CODE_OF_CONDUCT.md) that we expect project participants to adhere to. Please read the [full text](CODE_OF_CONDUCT.md) to understand what actions will and will not be tolerated.

## Community

### Status & bugs

Currently Trend Vision One GitHub is under heavy development. If you wish to report bugs or request new features, you can use the [Github issues module](https://github.com/trendmicro/tm-v1-containersecurity/issues).

### Discussion

If you need support or you wish to engage a discussion about the Trend Vision One platform, feel free to join us on our [Forums](https://success.trendmicro.com/forum/s/topic/0TO4T000000LH90WAG/trend-micro-vision-one).

### Support

Supports will be provided through the community. As this is an OSS project but not a formal Trend Micro product, formal product support is not applied.

## About

### Authors

Trend Vision One is a product designed and developed by the company [Trend Micro](https://www.trendmicro.com).

<a href="https://www.trendmicro.com" alt="Trend Micro"><img src="https://www.trendmicro.com/content/dam/trendmicro/global/en/core/images/logos/tm-logo-red-white-t.svg" width="230" /></a>

