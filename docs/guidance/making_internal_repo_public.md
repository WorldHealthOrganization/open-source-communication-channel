# Making an Internal GitHub Repository Public

## 📃 Open Source Checklist

You may want to make an internal repository public so that the work within it is available to everyone including those who do not have direct access to the repository. It is recommended that only repositories that have been licensed as open source be made public.

### Must have:

✅ An open source [LICENSE](choosing_a_license.md#license-reference) file

✅ A [copyright notice](choosing_a_license.md#copyright-notice)

### Recommended to have:

☑ A [README](sample_readme.md) file

☑ A [CONTRIBUTING](developing_contribution_guide.md) guide

☑ A community [CODE_OF_CONDUCT](https://github.com/WorldHealthOrganization/open-source-communication-channel/blob/main/CODE_OF_CONDUCT.md ':target=_blank') 

## 🔐 Security Checklist

It is critical to ensure that there is no sensitive material in the code files, documentation, history, issues, pull requests, or discussions before you make an internal repository public. The best approach to ensure that no sensitive material is shared in code files, documentation, issues, pull requests or discussions even when the repository is internal.

✅ Add [branch protection rules](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches ':target=_blank') to maintain control over contributions to the main branch.

✅ Review all code and remove any hard-coded sensitive information like passwords and emails. Note that the information may still be contained in the file's history even after deletion. 

> 📖 **Read more:** [Removing sensitive information from a repository](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository ':target=_blank')

> ❗ **Once you have pushed a commit to GitHub, you should consider any sensitive data in the commit compromised. If you have committed a password, you should change it. If you have committed a key, generate a new one. Removing the compromised data doesn't resolve its initial exposure, especially in existing clones or forks of your repository.**

☑ Add [tools for code scanning](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning#about-tools-for-code-scanning ':target=_blank') to your workflow.

## 🔗 Links to Useful Resources

- [Code security guides](https://docs.github.com/en/code-security/guides)

## 💬 How the Open Source Programme Office Can Support Your Work

If you have questions, would like to make an existing project open source, or start a new project that you would like to be open source, please reach out on [Discussions](https://github.com/WorldHealthOrganization/open-source-communication-channel/discussions).
