# Intro to Releases as a Workflow Trigger
A repo to help demonstrate the use of releases and creating/updating from workflows

The trigger for all of this could vary, but this repo is set up to have someone create a release (UI, API call, etc.) which will ick off a workflow that builds an applicaition (fictional in this repo), add comments/description to the release, and generate release notes.

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

I am adding more content to demonstrate release notes creation on release creation. I added this code change as a direct commit to main and no release note info was available.

I will add content through PRs to show Release Note content.

