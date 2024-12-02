# Triangle of Alexandria

Community sourced library of useful 3D computer graphics documents, resources, and tools.

# Submission Guidelines

The target audience is professional graphics programmers. Accepted categories include:
* Rendering technique PDFs
* Manuscripts on algorithms
* Small development tools
* Software libraries
* Documentation

Artifacts smaller than 10 megabytes must be directly uploaded to the repository, otherwise a link should be submitted. Important, yet large resources may also be uploaded directly. Care should be taken to assure that all resources are as small as possible without impacting usability. Artifacts that can be directly uploaded are preferable to links because of the ephemeral nature of the web.

Types of Artifacts:
* PDFs: Use a PDF compression tool to ensure its size is minimal.
* Links: Links to large resources should should be saved as a .desktop file with the executable permission set.
* Webpages: Small webpages should be downloaded into a folder and trimmed of ads, irrelevant comment sections, and their resources crunched. Attribution and styling should be kept, as long as styling isn't excessive.
* Executables: *THE CURATOR WILL PACKAGE EXECUTABLES*. Executables should be compressed into a zip or other archival format. The zip should be placed in a folder alongside documentation. Flatpaks and other containers are not accepted. Executables should be fairly feature complete and not require frequent updates.

Naming Convention: `Triangle-of-Alexandria[Dec-2-2024].pdf` Filenames must be ascii and contain no spaces or special characters, and cannot begin with a `.` character. The short title should be seperated with dashes. The date should be the most recent revision of the artifact, as precise as readily available.

Executable Naming Convention: `program-1.3-linux-x86_64.tar.gz`

.desktop file format example:
```
[Desktop Entry]
Name=Triangle of Alexandria
Type=Link
URL=https://github.com/rnvannatta/triangle-of-alexandria/
Icon=text-html
```

Submission requests should include a short justification for inclusion in the notes. A library curator will review the submission request, merging it into the collection if it is deemed worthy of the library.

Executables should should always be submitted as a link: the merge request should include an estimated size of the executable and documentation. The curator will package the executable into this repository if it is small.

These guidelines are subject to feedback and change as the Triangle of Alexandria grows and matures.
