# Amazon IVS CloudWatch Dashboard Sample

The reference solution show you how to create a CloudWatch dashboard that monitors usage, changes in stream state, and breaches of limits across all of your IVS live streams. We also explore creating alarms that you can use to detect if your streams experience a failure or otherwise move outside of normal performance expectations.

The solution taps into CloudWatch metrics emitted by Amazon IVS, as well as an event processor solution which takes Events emitted by Amazon IVS and converts these into CloudWatch Metrics.

## Launching solution with Pre-built AWS CloudFormation Template
To deploy the solution, use one of the following CloudFormation templates and follows the instructions.

| AWS Region | AWS CloudFormation Template URL |
|:-----------|:----------------------------|
| EU (Ireland) |<a href="https://console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/new?stackName=ivs-cw-dashboard&templateURL=https%3A%2F%2Fivsqos-github-templates-us-east-1.s3.amazonaws.com%2Fcw%2Fdeployment_template.yaml" target="_blank">Launch stack</a> |
| US (N.Virginia) |<a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=ivs-cw-dashboard&templateURL=https%3A%2F%2Fivsqos-github-templates-us-east-1.s3.amazonaws.com%2Fcw%2Fdeployment_template.yaml" target="_blank">Launch stack</a> |
| US (Oregon) |<a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=ivs-cw-dashboard&templateURL=https%3A%2F%2Fivsqos-github-templates-us-east-1.s3.amazonaws.com%2Fcw%2Fdeployment_template.yaml" target="_blank">Launch stack</a> |

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
