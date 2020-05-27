#  System Read permission demo, and how to contribute

Presented by [Tim Jacomb](https://www.jenkins.io/blog/authors/timja/).

Tim will take us through the System Read permission and the new ‘read-only’ Jenkins UI.
We will enable System Read, see what’s available in each of the 3 read-only permissions and then will do a dive into the code,
showing some of strategies required for controls to behave in a read-only manner.
Then we will try and add system read support to a plugin during the demo.


## Recording

[![Recording link](https://img.youtube.com/vi/Wy8PdkS0kjQ/0.jpg)](http://www.youtube.com/watch?v=Wy8PdkS0kjQ)

## Links

* Recording: http://www.youtube.com/watch?v=Wy8PdkS0kjQ
* Slides: [PDF](./slides.pdf)
* Announcement blog: https://www.jenkins.io/blog/2020/05/25/read-only-jenkins-announcement/
* Jenkins JEP-224: https://github.com/jenkinsci/jep/tree/master/jep/224

## Contributing

### Issues for grabs

* https://issues.jenkins-ci.org/browse/JENKINS-12548
* https://github.com/orgs/jenkinsci/projects/4

### How to update plugins?

* https://www.jenkins.io/blog/2020/05/25/read-only-jenkins-announcement/#how-do-i-update-my-plugin-to-support-it

### How to test?

* Setup Jenkins && enable permissions like in https://www.jenkins.io/blog/2020/05/25/read-only-jenkins-announcement/#how-can-i-use-it or https://www.jenkins.io/doc/developer/views/read-only/#enabling-permissions-that-use-read-only-views
* Install plugins, try them out with Agent, Job and System configurations
* Report discovered issues in Jira or GitHub


Meetup page: https://www.meetup.com/Jenkins-online-meetup/events/270775558/
