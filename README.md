# Triangle of Alexandria

Community sourced library of useful 3D computer graphics documents, resources, tools, and other artifacts.

Our mission is to create a curated archive of educational computer graphics artifacts that can survive being burned down. You are encouraged to clone this repository for that reason.

# Submission Guidelines

The target audience is professional graphics programmers. Accepted categories of artifacts include:
* Rendering technique PDFs
* Manuscripts on algorithms
* Small development tools
* Software libraries
* Documentation

Artifacts smaller than 10 megabytes should be be directly uploaded to the repository, otherwise a link should be submitted. Important, yet large resources may also be uploaded directly. Care should be taken to assure that all resources are as small as possible without impacting usability. Artifacts that can be directly uploaded are preferable to links because of the ephemeral nature of the web.

Types of Artifacts:
* Webpages: Small webpages should be downloaded into a folder and trimmed of irrelevant comment sections, fluff, and their resources crunched. Attribution and styling should be kept, as long as styling isn't excessive.
* Executables: *THE CURATOR WILL PACKAGE EXECUTABLES*. Executables should be compressed into a zip or other archival format. The zip should be placed in a folder alongside documentation. Flatpaks and other containers are not accepted. Executables should be fairly feature complete and not require frequent updates.
* PDFs: Use a PDF compression tool to ensure its size is minimal.
* Links: Links to large resources should should be saved as a .desktop file with the executable permission set.

Naming Convention: `Triangle-of-Alexandria[Dec-2-2024].pdf` File names and folder names must be ascii and contain no spaces or special characters, and cannot begin with a `.` character. The short title should be seperated with dashes. The date should be the most recent revision of the artifact, as precise as readily available.

Executable Naming Convention: `program-1.3-linux-x86_64.tar.gz` 

.desktop file format example:
```
[Desktop Entry]
Name=Triangle of Alexandria
Type=Link
URL=https://github.com/rnvannatta/triangle-of-alexandria/
Icon=text-html
```

Submission requests should include a short justification for inclusion in the notes. A library curator will review the submission request, merging it into the collection if it is deemed worthy of the library. Check BANNED.md before submitting a request.

Executables should should always be submitted as a link: the merge request should include an estimated size of the executable and documentation. The curator will package the executable into this repository if it is small.

These guidelines are subject to feedback and change as the Triangle of Alexandria grows and matures.

# Copyright

If your artifact is archived into the Triangle of Alexandria and you wish it removed, please submit a request by email ( triangleofalexandria at g mail dot com ) or by filing an issue on github. Please include all relevant information on why you are requesting the artifact removed. We will open a review and make a determination of what to do about the artifact. 

Pay special attention to which version of content you download. In general, journal articles from non-open-access journals such as those from ACM cannot be uploaded, even if they are sourced from the author's website. In such cases, only preprints published with a creative commons license can be uploaded to the Triangle. Software artifacts must be free software.

A list of websites restricted from artifact archival is maintained in BANNED.md.
