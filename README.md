# ng-ttt-template
Unofficial AsciiDoc template for the Newgrounds Tank Tribute.

## Usage

Download the files as a zip (code > download zip in the dropdown) and extract the files to a folder. Install the AsciiDoc extension for VS Code, and open the .adoc file in VS Code to get started.

## Caveats

Since this template is designed to take the output from VS Code's AsciiDoc Preview and paste it directly into the Newgrounds newspost box, the blank lines between paragraphs get eaten up in the process. As a workaround, `{sp} +` should be put on a blank line like so

{sp} +

Whenever an empty line between two paragraphs is intended (which is most of the time). There might be other ways to handle this more gracefully but I haven't tried them out yet.
