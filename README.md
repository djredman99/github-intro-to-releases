# Intro to Releases as a Workflow Trigger
A repo to help demonstrate the use of releases and creating/updating from workflows

The trigger for all of this could vary, but this repo is set up to have someone create a release (UI, API call, etc.) which will kick off a workflow that builds an application (fictional in this repo), adds comments/description to the release, and generates release notes.

*DEMO SCENARIO*
1. Make code change
2. Open PR
3. Generate Release and set to draft
4. Show that no assets are present
5. Publish the draft
6. Show workflow kicking off
7. Show completed Release and Release Notes

*TODO*
- Have the release move from **Pre-release** to **Latest** upon successful completion of the workflow.
- Use a release.yml to show how to customize the release notes

## What are Releases
Releases are deployable software iterations you can package and make available for a wider audience to download and use.

Releases are based on Git tags, which mark a specific point in your repository's history. A tag date may be different than a release date since they can be created at different times. For more information about viewing your existing tags, see [Viewing your repository's releases and tags](https://docs.github.com/en/repositories/releasing-projects-on-github/viewing-your-repositorys-releases-and-tags).

You can receive notifications when new releases are published in a repository without receiving notifications about other updates to the repository. For more information, see [Viewing your subscriptions](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/managing-subscriptions-for-activity-on-github/viewing-your-subscriptions).

Anyone with read access to a repository can view and compare releases, but only people with write permissions to a repository can manage releases. For more information, see [Managing releases in a repository](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).

You can manually create release notes while managing a release. Alternatively, you can automatically generate release notes from a default template, or customize your own release notes template. For more information, see [Automatically generated release notes](https://docs.github.com/en/repositories/releasing-projects-on-github/automatically-generated-release-notes).



I am adding more content to demonstrate release notes creation on release creation. I added this code change as a direct commit to main and no release note info was available.

I will add content through PRs to show Release Note content.

