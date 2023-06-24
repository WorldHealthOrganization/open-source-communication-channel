# Starting an Open Source Project

This document provides some quick pointers as you plan to make your work publicly available under and Open Source license.

## 🤔 What is Open Source? 

The term “Open Source” refers to Open Source software, which is code designed to be publicly accessible by anyone to study, use, modify and distribute. 

Historically, most software was “free and open” in the sense that it was developed by computer science academics and corporate researchers working together and distributing results under the principles of transparency, sharing and co-operation. However, the late 1960’s and especially the development of personal computers brought new opportunities to define a separate market for software: Since software is covered by copyright, which along with contract law provides a legal basis for its owner to establish exclusive rights, these rights were assigned or licensed under individual terms depending on the underlying business model. Consequently, hardware and software components were sold separately and under different conditions, whereby software was usually sold and distributed in “object code” format only, which is difficult for humans to understand, analyze or modify.

While this distinction between human-readable source code and machine-readable object code reflects a legitimate business model, some critics have argued that users should be able to study and change the software in use, e.g. to remove malicious elements or identify and address security issues, without having to rely on updates and support from respective software vendors. Hence, the main goal for the Free Software software approach is **not** to make software available free of charge but **free of legal constraints** that restrict studying and modifying software. In order to assure availability without restraints upon modification and redistribution, Free Software is released under public licenses reflecting the following four freedoms (see https://www.gnu.org/philosophy/free-sw.html):

- The freedom to run the program as you wish, for any purpose (freedom 0).
- The freedom to study how the program works, and change it so it does your computing as you wish (freedom 1). Access to the source code is a precondition for this.
- The freedom to redistribute copies so you can help others (freedom 2).
- The freedom to distribute copies of your modified versions to others (freedom 3). By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.

While the general idea of Free Software was very successful, the terminology was difficult to be adopted by the corporate sector. Because the English language does not differentiate between low price and liberty (or gratis and libre in other languages), the term Free Software invariably required further explanation. As a result of the debate with the corporate world, the term Open Source software was suggested as an alternative and as a strategic decision to “promote the idea of Free Software to business people” (see https://www.theregister.com/2018/02/03/open_source_turns_20/). Like the Free Software advocates, supporters of the Open Source software concept establshied a set of criteria for licensing terms to qualify as Open Source conformant, see OSI definition available at https://opensource.org/osd/.

Even if both terms and definitions exist in parallel, the ultimate goal of both the Free Software advocates and the Open Source Software supporters remains the same: Software should be available under legal terms that allow and facilitate studying, modifying and further distributing the software. 

## 📄 Open Source Licenses 

> ℹ **Note:** A project becomes Open Source once an **Open Source license is applied** to it, and the source code is made **available to the public**.

As per definition, all Open Source licenses require that the respective source code must be publicly available and that modification must be allowed. However, a detailed look into the terms of different Open Source licenses reveals that they can be devided into different categories: 
- Copyleft licenses require further licensees, who modify the software, to make such modifi-cations available under the same terms under which the original software was released with-out any further restrictions.
- Permissive licences give the user the flexibility in the sense that they do not restrict the use of the software and do not impose any conditions as to which the software itself or any modification have to be used or subsequently licensed.  Consequently software licensed under a permissive license may be modified and distributed under any license including a non open source license for example a proprietary license. 

Popular Copyleft licenses include
- [GNU General Public License version 2.1]
- [GNU General Public License version 3.0](https://www.gnu.org/licenses/gpl-3.0.html)

Popular permissive licenses include
- [BSD License] 
- [MIT License](https://mit-license.org/)
- [Apache License, Version 2.0](https://httpd.apache.org/docs/2.4/license.html)

> ℹ **Note:** Not all open source licenses are copyleft.

## How to start an Open Source project: Best Practices

GitHub's [opensource.guide](https://opensource.guide/starting-a-project/) provides an easy to follow checklist to help you if you want to open source your project:

### Documentation

✔ GitHub repository - the [WHO has adopted GitHub](new_github_repo.md) as the standard code repository for software projects

✔ License - add a LICENSE file containing your chosen open source license to your project

✔ Basic documentation - add [README](sample_readme.md), CONTRIBUTING, and CODE_OF_CONDUCT files to guide people who want to know more about the project and perhaps contribute to it

### Code

✔ Conventions and best practices - use consistent code conventions and practices to make your work easily maintainable 

✔ Continuous documentation - add code comments or inline documentation

> 💡 **Hint:** If you wanted to contribute to an open source project, what practices would make it easier for you? Apply the same to encourage your community to contribute to your work.

### Community and Collaboration

✔ Promote your project internally and externally

✔ Assign a community manager to handle interaction with your community


## 🔗 Links to Useful Resources

- [List of Open Source licenses approved by the Open Source Initiative](https://opensource.org/licenses)
- [The legal side of open source](https://opensource.guide/legal/)

## 💬 How the Open Source Programme Office Can Support Your Work

If you have questions, would like to make an existing project open source, or start a new project that you would like to be open source, please reach out on [Discussions](https://github.com/WorldHealthOrganization/open-source-communication-channel/discussions).
