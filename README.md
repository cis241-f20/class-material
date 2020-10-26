# Welcome to CIS 241 - System-level Programming and Utilities, Fall 2020

## About the Course

### Course Overview
This course should help acquaint you with:

* Navigating and using a Unix-based OS (primarily Linux)
* Remote access and file transfer for Unix systems
* Linux utilities and scripting
* Git/Github
* Programming with a system-level language (C) and memory management

### Helpful Links

* [Syllabus](syllabus.md)
* [Piazza](https://piazza.com/class/kdru22j5k4n3si) -- also [FAQ about Piazza](piazza-faq.md)
* [PrairieLearn](https://prairielearn.engr.illinois.edu/) - log-in
  using "Google" and use your GVSU gmail account
* [ClassTranscribe](https://classtranscribe.com/offering/2eda65cf-d00f-4a0b-bb00-7bba2f88ccc6) -
  select "Google" sign-in and use your GVSU gmail account
* [GVSU VPN Instructions](https://www.gvsu.edu/it/downloading-installing-and-setting-up-pulse-secure-222.htm)

### Need Help?
If you have questions, please ask!  I'm here to help -- it'll
just take place in a virtual format.  I welcome students
to just sign-on to the office hour zoom calls and use the time
to work on their projects and listen to questions others might have.

### COVID
Unfortunately, this will not be a typical semester.  This course
will be entirely online, but there will still likely be
surprises and we will need to be flexible to accommodate changes.

I recognize the difficulties some of you may face.
My goal is to make this semester as effective and as smooth
as possible.  Please reach out to me early and keep me informed
of any issues that arise.

### Course Schedule
This table will have all of the lecture video links, due dates, etc.
added throughout the semester.  Material will be added on a weekly basis.
Lecture video links will be posted under the topic column and released
at the start of each week.

| Week | Date          | Topics | Activities | TODOs |
| ---- | ------------- | ------ | ---------- | --------- |
|  01  | 08/31 - 09/04 | intro [video](https://classtranscribe.com/video?id=fea96de7-2ea2-46f2-ad73-a0d595ece7c7) <br> ssh [video](https://classtranscribe.com/video?id=31cc47d8-5003-47f4-9c82-33085bf87f0f) [slides](lec-notes/lec01-intro-ssh.pdf) <br> navigating linux [video](https://classtranscribe.com/video?id=e5177a6d-2151-4fdf-836c-512fb733b677) [slides](lec-notes/lec02-linux-filesystem-basics.pdf) <br> file transfer [video](https://classtranscribe.com/video?id=f82ca560-7708-4204-8687-a6e41b563043) [slides](lec-notes/lec03-scp-rsync.pdf)  | [minilab 1](minilabs/minilab01.md) | Create a [Piazza account](https://piazza.com/class/kdru22j5k4n3si) <br> Create a [github](https://github.com/) account (if you do not already have one <br> [Course Survey due Friday 09/04](https://forms.gle/zoiNaFCJq5PJeFea7) |
|  02  | 09/07 - 09/11 | LABOR DAY (09/07) <br> sshkeys [video](https://classtranscribe.com/video?id=43fbb05d-b355-4bc0-a0c7-e72658a23892) [slides](lec-notes/lec04-sshkeys-aliases.pdf) <br> script/history [video](https://classtranscribe.com/video?id=068ca65e-35fe-446f-aae5-a9124421ff30) [slides](lec-notes/lec05-history.pdf) <br> IO redirection [video](https://classtranscribe.com/video?id=8c29f20f-8aba-4b5a-899a-8f722f57051f) [slides](lec-notes/lec06-redirection.pdf) <br> linux utilities [video](https://classtranscribe.com/video?id=49c9805b-f410-4101-b07f-3653747ff726) [slides](lec-notes/lec07-cut-tr-wc.pdf) | [minilab 2](minilabs/minilab02.md) | - |
|  03  | 09/14 - 09/18 | compression [video](https://classtranscribe.com/video?id=cdfbf1dd-980c-4b41-8eaa-e74795e07b88) [slides](lec-notes/lec08-compression.pdf) <br> linux utilities [video](https://classtranscribe.com/video?id=904ac7b5-4e58-431c-abc9-28b476952caf) [slides](lec-notes/lec09-diff-piping.pdf) <br> grep [video](https://classtranscribe.com/video?id=8e6e4aab-0830-4b72-91d8-bc9cde6f38d2) [slides](lec-notes/lec10-grep-wildcards.pdf) <br> git overview [video](https://classtranscribe.com/video?id=881e9710-2f41-4461-972c-ec0f32ae59b3) [slides](lec-notes/lec11-git-overview.pdf) | [minilab 3](minilabs/minilab03.md) | [Project 1 Released](https://prairielearn.engr.illinois.edu/pl/) |
|  04  | 09/21 - 09/25 | git intro [video](https://classtranscribe.com/video?id=d262dd4b-00e4-4577-8cf8-aa72be163afd) [slides](lec-notes/lec12-git-intro.pdf) <br> git branching [video](https://classtranscribe.com/video?id=e48a0506-df26-469a-8dbb-c077bffa5cdb) [slides](lec-notes/lec13-git-branching.pdf) <br> git remotes [video](https://classtranscribe.com/video?id=136309e0-3c8e-4e1a-b8c4-5fc2137ca217) [slides](lec-notes/lec14-git-remotes.pdf) <br> git merging [video](https://classtranscribe.com/video?id=007102b0-516f-4dcd-a19d-344147d6c69a) [slides](lec-notes/lec15-git-merging.pdf) | [minilab 4](minilabs/minilab04.md) | - |
|  05  | 09/28 - 10/02 | git other [video](https://classtranscribe.com/video?id=75e64886-9200-40ae-bcb6-de8067e81b89) [slides](lec-notes/lec16-git-other.pdf) <br> vim [video](https://classtranscribe.com/video?id=497b23a2-028f-4df5-b09b-2a4b765847cf) [slides](lec-notes/lec17-vim.pdf) <br> permissions/path [video](https://classtranscribe.com/video?id=743529da-3864-4be1-b7f7-2d3d26e7095a) [slides](lec-notes/lec18-permissions-path.pdf) <br> processes [video](https://classtranscribe.com/video?id=891e22dc-d70e-4c4a-91e9-4ca25c27da51) [slides](lec-notes/lec19-processes.pdf) | [minilab 5](minilabs/minilab05.md) | Project 1 Due 10/02 |
|  06  | 10/05 - 10/09 | Bash Scripting <br> basics [video](https://classtranscribe.com/video?id=91542cf6-4f84-41d4-9108-e4aee7e7c814) [slides](lec-notes/lec20-bash-scripting-basics.pdf) [script](misc-files/week6/bash-scripts/basic.sh) <br> arguments [video](https://classtranscribe.com/video?id=647eda3e-b36a-46ff-ab83-5343b9705fba) [slides](lec-notes/lec21-bash-scripting-arguments.pdf) [script](misc-files/week6/bash-scripts/arguments.sh) <br> variables [video](https://classtranscribe.com/video?id=36835a8e-ac0f-40c7-a56a-c6d075fff562) [slides](lec-notes/lec22-bash-scripting-variables-arithmetic.pdf) [script](misc-files/week6/bash-scripts/variables.sh) <br> conditionals [video](https://classtranscribe.com/video?id=10e2208d-771e-416f-83b6-1f58cc476560) [slides](lec-notes/lec23-bash-scripting-conditionals.pdf) [script](misc-files/week6/bash-scripts/conditionals.sh) <br> loops [video](https://classtranscribe.com/video?id=1a488428-4ac1-417e-9378-6790c565b6bd) [slides](lec-notes/lec24-bash-scripting-loops.pdf) [script](misc-files/week6/bash-scripts/loops.sh) <br> arrays [video](https://classtranscribe.com/video?id=dabb2916-5171-44d0-bc54-17cbcf630e06) [slides](lec-notes/lec25-bash-scripting-arrays.pdf) [script](misc-files/week6/bash-scripts/arrays.sh) <br> functions [video](https://classtranscribe.com/video?id=1a1227fd-394b-41a8-a743-065af7571de5) [slides](lec-notes/lec26-bash-scripting-functions.pdf) [script](misc-files/week6/bash-scripts/functions.sh) | [minilab 6](minilabs/minilab06.md) | - |
|  07  | 10/12 - 10/16 | regex basics [video](https://classtranscribe.com/video?id=d3cb9c39-fe39-427c-a626-afdc54a903b5) [slides](lec-notes/lec27-regex.pdf) <br> regex and grep [video](https://classtranscribe.com/video?id=60fa61e7-4243-4047-8ae8-2d71d058462c) [slides](lec-notes/lec28-regex-grep.pdf) <br> sed [video](https://classtranscribe.com/video?id=0f63ff5a-dfc5-4361-bdf9-383772d690c2) [slides](lec-notes/lec29-sed.pdf) | [minilab 7](minilabs/minilab07.md) <br> [solution video](https://classtranscribe.com/video?id=665bc2c3-54ef-4ee4-b821-2f54afcab158) | [Project 2 Released](https://prairielearn.engr.illinois.edu/pl/) |
|  08  | 10/19 - 10/23 | gawk basics [video](https://classtranscribe.com/video?id=4fd70483-5289-40d7-9489-1f2bd69e0f0d) [slides](lec-notes/lec30-gawk-basics.pdf) [script](misc-files/week8/script-basics.awk) <br> gawk adv [video](https://classtranscribe.com/video?id=684266bc-7be4-400e-8fea-1a194672aa4a) [slides](lec-notes/lec31-gawk-advanced.pdf) [script](misc-files/week8/script-advanced.awk) <br> C intro [video](https://classtranscribe.com/video?id=711bfa10-2296-4571-96e3-7441a89de8ec) [slides](lec-notes/lec32-c-intro.pdf) | [minilab 8](minilabs/minilab08.md) | - |
|  09  | 10/26 - 10/30 | C compiling [video](https://classtranscribe.com/video?id=7b7645ec-3fa3-4c8c-bf04-0dcd79536df5) [slides](lec-notes/lec33-c-compiling.pdf) <br> C printing [video](https://classtranscribe.com/video?id=36343308-b4f6-4500-bf0d-79a841141d71) [slides](lec-notes/lec34-c-types-print.pdf) [script](misc-files/week9/types-printing.c) <br> C basics [video](https://classtranscribe.com/video?id=9aba1043-3a71-4df0-ac89-1fbf7b8edd92) [slides](lec-notes/lec35-c-operations-conditionals.pdf) [script](misc-files/week9/ops-cond.c) <br> C loops [video](https://classtranscribe.com/video?id=6b1dff74-7750-46e6-9a68-7abb85d852d5) [slides](lec-notes/lec36-c-loops.pdf) [script](misc-files/week9/loops.c) <br> C pointers [video](https://classtranscribe.com/video?id=8be8a41e-10e8-4fc7-9d6a-5eb0260357c2) [slides](lec-notes/lec37-c-pointers.pdf) [script](misc-files/week9/pointers-intro.c) | TBA | Project 2 Due 10/31 |
|  10  | 11/02 - 11/06 | Midterm Wednesday 11/04 <br> C stack vs heap, arrays & pointers | TBA | TBA |
|  11  | 11/09 - 11/13 | C input, functions, switch, header files | TBA | TBA |
|  12  | 11/16 - 11/20 | C structs, 2d arrays| TBA | TBA |
|  13  | 11/23 - 11/27 | makefiles <br> THANKSGIVING RECESS (11/25-11/27) | TBA | TBA |
|  14  | 11/30 - 12/04 | C string funcs, debugging, enums-unions | TBA | TBA |
|  15  | 12/07 - 12/11 | fileio, arguments, libraries, recap | TBA | TBA |
|  16  | 12/14 - 12/18 | FINAL EXAM WEEK -- DAY TBD | TBA | TBA |
