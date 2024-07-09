# inblog for GitHub Pages

1. [Click here to create a repository based on this template](https://github.com/new?template_name=inblog-pages-template&template_owner=weebney)
1. In your new repo, go to the "Settings" tab
1. Under the "Security" section, click on the "Secrets and variables" dropdown; in the dropdown menu, select "Actions"
1. Click on "New repository secret"
1. You must set the following secrets:
  - INBLOG_EMAIL
  - INBLOG_PASSWORD
  - INBLOG_IMAPSSERVER
  - INBLOG_MAILBOX
  - INBLOG_APPROVED_SENDER
  - INBLOG_NAME
6. Once these are set, click on "Pages" in the left menu
1. Under "Build and deployment," click the source dropdown and select "GitHub Actions"
1. In the top menu, go to the "Actions" tab of the repository
1. In the menu on the left, click on "Run inblog"
1. A blue banner should appear that reads "This workflow has a workflow_dispatch event trigger" ; on the right of the banner, click on "Run workflow" and then "Run workflow" in the dropdown menu
1. This should build and deploy your blog.

Notes:
- inblog will run automatically everyday at midnight UTC
- To add custom CSS, you can add CSS files to the `public/` directory and reference them in the `content/templates` template files
