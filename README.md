# CICADA technical documentation site

This repository contains a small static documentation site: HTML, CSS and no
JavaScript, build framework, remote fonts or analytics. It is documentation,
not the CICADA product repository or a parallel API specification. Authoritative
code, contracts, runtime instructions and acceptance records live on
[cicada dev](https://github.com/cicada-fabric/cicada/tree/dev).

GitHub Pages hosting configuration and public HTTP availability must be verified
separately. Preparing or pushing these files does not prove the site is live.
No publishing workflow or product release is created here. First-party material
is [Apache-2.0](LICENSE); third-party material retains its own terms.

## Configure GitHub Pages

After the source is pushed, an authorized repository administrator can open
Settings → Pages, choose **Deploy from a branch** under Build and deployment,
select **main** and **/(root)**, then Save. The root `index.html` is the entry
point and `.nojekyll` disables Jekyll processing. This uses GitHub's branch
publishing service without adding a custom workflow or build dependency.
Verify the deployment status and the actual public HTTP page afterward; these
instructions do not claim the setting has been applied or the site is live.
See [GitHub's publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
