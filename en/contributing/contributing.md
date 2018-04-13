# Contributing to MAVLink

We follow the [Github flow](https://guides.github.com/introduction/flow/) development model. Contributions fall into two main categories: Design and micro-service changes include new features that come with a state machine and message specifications for a new type of interface (examples: parameter or mission protocol). These are major contributions requiring a lot of vetting and should come with a RFC pull request in https://github.com/mavlink/rfcs. Protocol specification and documentation changes are usually changes with less impact and can be directly raised as pull requests against this repository.

Below we explain the processes for contributing to each category and how to raise a pull request.

## How to Contribute Design and Micro-service Changes

* Open a pull request against the RFC repository containing a new RFC number https://github.com/mavlink/rfcs and use the template in the 0000 RFC.
* Reach out to the community on Slack and on http://discuss.dronecode.org to raise awareness
* Address concerns by pushing more commits to the pull request
* Mavlink RFC are discussed on a weekly basis in the Mavlink RFC call. See the [Dronecode Calendar](#calendar).

## How to Contribute Protocol Specification Changes

* Open a pull request against the specification repository: https://github.com/mavlink/mavlink
* Reach out to the community on Slack and on http://discuss.dronecode.org to raise awareness
* Address concerns by pushing more commits to the pull request
  
## How to Open a Pull Request

1. First [fork and clone](https://help.github.com/articles/fork-a-repo) the project project.
1. Create a feature branch off master
   ```
   git checkout -b mydescriptivebranchname
   ```
   > **Note** *Always* branch off master for new features.
1. Commit your changes with a descriptive commit message.
   * Include context information, what was fixed, and an [issue number](https://github.com/mavlink/mavlink) (Github will link these then conveniently)
   * **Example:**

     ```
     Change the attitude output spec documentation

     - Fixes a typo
     - Clarifies that units are radians

     Fixes issue #123
     ```

1. Test your changes (we may ask you for test results in your PR).
1. Push changes to your repo:
   ```
   git push origin mydescriptivebranchname
   ```
1. Send a [pull request](https://github.com/mavlink/mavlink/compare/) to merge changes in the branch.


## Calendar & Events {#calendar}

The *Dronecode Calendar* shows important events for platform developers and users. 
Select the links below to display the calendar in your timezone (and to add it to your own calendar):
* [Switzerland – Zurich](https://calendar.google.com/calendar/embed?src=linuxfoundation.org_g21tvam24m7pm7jhev01bvlqh8%40group.calendar.google.com&ctz=Europe%2FZurich)
* [Pacific Time – Tijuana](https://calendar.google.com/calendar/embed?src=linuxfoundation.org_g21tvam24m7pm7jhev01bvlqh8%40group.calendar.google.com&ctz=America%2FTijuana)
* [Australia – Melbourne/Sydney/Hobart](https://calendar.google.com/calendar/embed?src=linuxfoundation.org_g21tvam24m7pm7jhev01bvlqh8%40group.calendar.google.com&ctz=Australia%2FSydney)

**Note:** calendar defaults to CET.


{% raw %}
<iframe src="https://calendar.google.com/calendar/embed?title=Dronecode%20Calendar&amp;mode=WEEK&amp;height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=linuxfoundation.org_g21tvam24m7pm7jhev01bvlqh8%40group.calendar.google.com&amp;color=%23691426&amp;ctz=Europe%2FZurich" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
{% endraw %}