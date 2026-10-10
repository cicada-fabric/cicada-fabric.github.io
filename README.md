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

Current text follows Core documentation checkpoint
[`c25dc731`](https://github.com/cicada-fabric/cicada/tree/c25dc731b41631993184211b65c8d0df14144c7a):
development software 0.0.1-dev, with initial 0.1.0 publication pending the user's
actual deployment/acceptance and separate authorization. The earlier site source
`88ce9e770d55dbe4108ba39f7586fa4666975378` remains in Git history. This update
changes current text and evidence links only, retaining the HTML structure,
stylesheet, dependency-free implementation and historical source attribution.

## Configure GitHub Pages

After the source is pushed, an authorized repository administrator can open
Settings → Pages, choose **Deploy from a branch** under Build and deployment,
select **main** and **/(root)**, then Save. The root `index.html` is the entry
point and `.nojekyll` disables Jekyll processing. This uses GitHub's branch
publishing service without adding a custom workflow or build dependency.
Verify the deployment status and the actual public HTTP page afterward; these
instructions do not claim the setting has been applied or the site is live.
See [GitHub's publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
