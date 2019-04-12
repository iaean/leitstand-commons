We definitely welcome your patches and contributions!  
If you are new to github, please start by reading [Pull Request](https://help.github.com/articles/about-pull-requests/) howto.

_TODO: require fork/PR pattern..._

### 👁️ Legal requirements

_Do we need Corporate Contributor License Agreements (CCLA)?_

e.g.: In order to protect both you and ourselves, you will need to sign the
[Contributor License Agreement](https://identity.linuxfoundation.org/projects/cncf).

### 🕵️ Building

Different languages use different build systems. 

_TODO: more content needed... (especially for docker stuff)_

### Guidelines for Pull Requests

How to get your contributions merged smoothly and quickly.

- Create **small PRs** that are narrowly focused on **addressing a single
  concern**.  We often times receive PRs that are trying to fix several things
  at a time, but only one fix is considered acceptable, nothing gets merged and
  both author's & review's time is wasted. Create more PRs to address different
  concerns and everyone will be happy.

- For speculative changes, consider opening an issue and discussing it first.
  
- Provide a good **PR description** as a record of **what** change is being made
  and **why** it was made. Link to a GitHub issue if it exists.

- Don't fix code style and formatting unless you are already changing that line
  to address an issue. PRs with irrelevant changes won't be merged. If you do
  want to fix formatting or style, do that in a separate PR.

- 👁️ Unless your PR is trivial, you should expect there will be reviewer comments
  that you'll need to address before merging. We expect you to be reasonably
  responsive to those comments, otherwise the PR will be closed after 3-4 weeks
  of inactivity.

- 👁️ If you have non-trivial contributions, please consider adding an entry to the
  [AUTHORS file](https://github.com/leitstand/commons/blob/master/AUTHORS.md) listing the
  copyright holder for the contribution (yourself, if you are signing the
  individual CLA, or your company, for corporate CLAs) in the same PR as your
  contribution. This needs to be done only once, for each company, or
  individual. Please keep this file in alphabetical order.

- 🕵️ Maintain **clean commit history** and use **meaningful commit messages**.
  PRs with messy commit history are difficult to review and won't be merged.
  _TODO: require squashing..._

- Keep your PR up to date with upstream/master! If there are merge conflicts,
  we can't really merge your change.

- 👁️ **All tests need to be passing** before your change can be merged.
  We recommend you **run tests locally** before creating your PR to catch
  breakages early on. Ultimately, the green signal will be provided by our
  testing infrastructure. The reviewer will help you if there are test failures
  that seem not related to the change you are making.

- Exceptions to the rules can be made if there's a compelling reason for doing so.
