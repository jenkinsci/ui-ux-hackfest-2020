# Demo: GitHub Checks API Plugin prototype for Jenkins

Presented by [Kezhi Xiong](https://www.jenkins.io/blog/authors/xiongkezhi/).

Kezhi show a prototype of the new GitHub Checks API Plugin for Jenkins which is being developed as a Google Summer of Code 2020 project.

The GitHub Checks API allows developers to report the CI integrations’ detailed information rather than the binary pass/fail build status on GitHub pages. This project is about implementing a new API plugin for Jenkins.
By consuming this API, other plugins can easily create new GitHub checks.
Thus, any information during the Jenkins process like warnings, summaries, and durations can be directly shown on GitHub pages.

We will show a demo of the plugin.
Then we will take a look at the current design including the basic logic and API design.
We would like to get more developers and users involved to help us determine what they want to see eventually in the GitHub Action pages.

## Recording

[![Recording link](https://img.youtube.com/vi/jx1_nxAPt0A/0.jpg)](http://www.youtube.com/watch?v=jx1_nxAPt0A)

## References

* Recording: https://www.youtube.com/watch?v=jx1_nxAPt0A
* Project page: https://www.jenkins.io/projects/gsoc/2020/projects/github-checks/
* Plugin repository: https://github.com/XiongKezhi/checks-api-plugin
GitHub Checks API: https://developer.github.com/v3/checks/
