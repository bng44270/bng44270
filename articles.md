## [Boot Story][boot story url]  (PXE Boot with TinyCore Linux)  
Published in Linux Pro Magazine January 2020 Issue  
  
## [Writing Github Web Hooks with Bash][github webhook url]  
Published in Linux Journal August 2019 Issue  
  
## [Bare-Bones Monitoring with Monit and RRDTool][bbmonit url]  
Published in Linux Journal November 2018 Issue  
  
## [Building a Bare-Bones Git Environment][bbgit url]  
Published in Linux Journal July 2018 Issue  
  
## [Bit Trip][bit trip url]  (manipulating binary data with Bash)  
Published in Linux Pro Magazine May 2018 Issue  
  
## [Developing Console Applications with Bash][bash dev url]  
Published in Linux Journal October 2017 Issue  
  
## [Integrating Web Applications with Apache][apache int url]  
Published in Linux Journal March 2017 Issue  

[boot story url]:  http://www.linuxpromagazine.com/Issues/2020/230/PXE-Boot-with-TinyCore
[github webhook url]:  https://www.linuxjournal.com/content/writing-github-web-hooks-bash
[bbmonit url]:  https://www.linuxjournal.com/content/bare-bones-monitoring-monit-and-rrdtool
[bbgit url]:  https://www.linuxjournal.com/content/building-bare-bones-git-environment
[bit trip url]:  http://www.linux-magazine.com/Issues/2018/210/Binary-Data-in-Bash
[bash dev url]:  https://www.linuxjournal.com/content/developing-console-applications-bash
[apache int url]:  https://www.linuxjournal.com/content/integrating-web-applications-apachecurl -L \
  -X PUT \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <YOUR-TOKEN>"\
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/OWNER/REPO/contents/PATH \
  -d '{"message":"my commit message","committer":{"name":"Monalisa Octocat","email":"octocat@github.com"},"content":"bXkgbmV3IGZpbGUgY29udGVudHM="}'
