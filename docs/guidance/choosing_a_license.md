# Choosing an Open Source License

Open source licenses are licenses that comply with the [OSI Open Source Definition](https://opensource.org/osd).

Before you choose an open source license, it is good to understand what you want to accomplish with your open source project.

You may want to:

- collaborate with contributor communities to develop new features or make improvements to your project
- make the project discoverable and openly available to anyone who want to use and modify it
- reduce duplication of solutions

Depending on your objectives, you might opt for a permissive license or non-permissive (copyleft) license.

The World Health Organization Legal team have reviewed various OSI approved licenses and recommend using one of these licenses:

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
Copyleft | These require you to apply a compatible open source license to derived works | GPL-v3, AGPL-v3
Weak copyleft | Some restrictions | LGPL 
Permissive | No restriction on licensing for derived works | Apache-2.0, MIT

Permissive licenses give people freedom to 

<br>

> 📖 **Read more:** [What is Copyleft?](https://www.gnu.org/licenses/copyleft.html)

<br>

## 📝 File Notice

Placed at start of file

#### License Reference

Unambiguous license reference.

#### Copyright Notice

Unambiguous copyright reference. For example:

> Copyright The World Health Organization, 2020 - 2022.

Note

Include first year of publication along with years in which additional copyrightable content was contributed to the project or file

or 

> Copyright The Health Project Contributors.



## Useful Links and Resources 

- [Choose an Open Source License](https://choosealicense.com/) - a site to help developers choose an open source license for the source code.
- [The Legal Side of Open Source](https://opensource.guide/legal/) - open source tips and resources from GitHub.
- [REUSE Specification](https://reuse.software/spec/) - a specification defines a standardized method for declaring copyright and licensing for software projects. The goal of the specification is to have unambiguous, human- and machine-readable copyright and licensing information for each individual file in a project.