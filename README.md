## First steps with ConcourseCI

Install (with docker): [https://concourse-ci.org/quick-start.html](https://concourse-ci.org/quick-start.html)  
Some `fly` commands: [https://concourse-ci.org/fly.html](https://concourse-ci.org/fly.html)


Basic commands:
  - Creating pipeline: `fly -t local sp -c pipeline.yml -p pipeline-name`
  - Unpause pipeline: `fly -f local up -p pipeline-name`
