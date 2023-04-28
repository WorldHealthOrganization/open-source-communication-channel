# Choosing an Open Source License

Open source licenses are licenses that comply with the [OSI Open Source Definition](https://opensource.org/osd).

Before you choose an open source license, it is good to understand what you want to accomplish with your open source project.

You may want to:

- collaborate with contributor communities to develop new features or make improvements to your project
- make the project discoverable and openly available to anyone who want to use and modify it
- reduce duplication of solutions

Depending on your objectives, you might opt for a permissive license or non-permissive (copyleft) license.

The some of the projects hosted on https://github.com/WorldHealthOrganization have reviewed and applied various OSI approved licenses including:

- [GNU General Public License (GPL) version 3](https://www.gnu.org/licenses/gpl-3.0.html) 
- [Apache License, Version 2.0](https://httpd.apache.org/docs/2.4/license.html)
- [MIT License](https://mit-license.org/)

GNU recommend different licenses for different projects, depending mostly on the software's purpose. In general, they recommend using the strongest copyleft license that doesn't interfere with that purpose. 

Here's a brief summary of what you need to do to release a program GNU GPL-v3:

✔ Get a copyright disclaimer from the organization's legal team 

> 💡 **Hint:** Use the the [README template](sample_readme.md) if unsure.

✔ Give each file the proper copyright notices. Make sure to clearly identify which versions of the license users can use.

✔ Add a COPYING file with a copy of the GNU GPL-v3.

✔ Put a license notice in each file.

🔘 (Optionally) make the program display a startup notice.


## 📑 License Types

Type     | Description | Examples
-------- | ----------- | --------
Copyleft | Provisions of the original license are imposed on all derivative work. Derivative work can be relicensed under a different copyleft license, but only if it is compatible with the original license. | GPL-v3, AGPL-v3
Weak copyleft | A compromise between strong copyleft and permissive licenses. It allows more flexibility in the provisions such as linking from code licensed under different types of licenses (even non-opensource ones) or incorporating code in larger software (even if it isn't copyleft). | LGPL 
Permissive | No restriction on licensing for derived works. | Apache-2.0, MIT

> 📖 **Read more:** [What is Copyleft?](https://www.gnu.org/licenses/copyleft.html)

For every license, there are things you **Can**, **Must**, and **Cannot** do.

> ℹ **Tip:** [Browse Software Licenses & Summaries](https://tldrlegal.com/licenses/browse) for simple, practical summaries of open source licenses.

## 🧩 License Compatibility 

It is important to identify the component parts of the software and their licenses in order to ensure compatibility with the licence that you plan to release the software under. 

> 📖 **Read more:** [GPL-Compatible Free Software Licenses](https://www.gnu.org/licenses/license-list.html#GPLCompatibleLicenses)

## 📝 File Notices

File notices are typically included at start of a software source file, indicating the license reference and copyright notices.

#### *License Reference*

It is recommended to put a LICENSE file at the root folder of the project and include the full text of the project license. 

Referring to the actual license within each source file in the project removes ambiguity, especially where multiple licenses are used.

For example:

```
// SPDX-License-Identifier: GPL-2.0-only
```

> 📖 **Read more:** [SPDX License List including a standardized short identifier, the full name, the license text, and a canonical permanent URL for common open source licenses.](https://spdx.org/licenses/)

or 

```
/*
 This program is free software; you can redistribute it and/or
 modify it under the terms of the GNU General Public License
 version 2 as published by the Free Software Foundation.

 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
 GNU General Public License for more details.
*/
```

#### *Copyright Notice*

Copyright notices can follow two models:

✔ the word "Copyright"

✔ the symbol ©

✔ a year or range of years

✔ the name of the individual or legal entity who is the copyright holder

For example:
```
// Copyright The World Health Organization, 2020 - 2022.
```

> ℹ **Note:** Include first year of publication along with years in which additional copyrightable content was contributed to the project or file

or 

✔ "Copyright Contributors to the _______ Project" or "Copyright The _______ Contributors"

For example:
```
// Copyright The Health Project Contributors.
```

## 🔗 Useful Links and Resources 

- [Choose an Open Source License](https://choosealicense.com/) - a site to help developers choose an open source license for the source code.
- [The Legal Side of Open Source](https://opensource.guide/legal/) - open source tips and resources from GitHub.
- [REUSE Specification](https://reuse.software/spec/) - a specification defines a standardized method for declaring copyright and licensing for software projects. The goal of the specification is to have unambiguous, human- and machine-readable copyright and licensing information for each individual file in a project.

## How the Open Source Programme Office Can Support Your Work

If you have questions, would like to choose an open source license or add file notices to your project, reach out on the [WHO open source discussions board](https://github.com/WorldHealthOrganization/open-source-communication-channel/discussions).