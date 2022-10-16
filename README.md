# android-github-actions-sample
Sample Android application that implements GitHub Actions

**Workflows:**
- [X] **build_pull_request.yml** - 
	1. Triggers on every new pull request. 
	2. Runs all the unit tests and uploads test reports to artifacts.
	3. Builds .apk file and uploads it to artifacts.

**To-Do:**
- [ ] Create a workflow to build a .apk file and share it with Firebase App Distribution.
- [ ] Create a workflow to build a .apk file and share it directly with Slack.
- [ ] Create a workflow to publish the app on the play store.
