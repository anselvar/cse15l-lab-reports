# Lab Report 2 Week 4   

## First Failed Test: [test-file-5](https://github.com/anselvar/markdown-parser/blob/main/test-file5.md)   
- fails since it shows a link rather than nothing (the correct output), even though there is text between the link name and the link.   
### Symptom of failure-inducing input
INSERT IMAGE   
### Commit that fixes this problem   
INSERT IMAGE   
### Reasoning:   
The reason this test fails (the bug) is because the program kept looking for the parentheses well after the brackets, which led to incorrect link identification. Rather than showing an output of nothing, it gives a link. This incorrect output is the symptom of this bug. The failure inducing input showed the symptom of a link being shown rather than a blank space.   
   
## Second Failed Test: [test-file-6](https://github.com/anselvar/markdown-parser/blob/main/test-file6.md)   
- fails since it shows a link rather than reading it as an image.   
### Symptom of failure-inducing input   
INSERT IMAGE   
### Commit that fixes this problem   
INSERT IMAGE   
### Reasoning:   
The bug in this program is that the images were not ignored and instead treated as links. The symptom of this bug is that the link was shown instead of being ignored as an image. The failure inducing input shows this symptom of an incorrect output.   
   
## Third Failed Test: [test-file-9](https://github.com/anselvar/markdown-parser/blob/main/test-file9.md)   
- fails since it reads the inner parenthetical as a link rather than recognizing that there is no link.   
### Symptom of failure-inducing input   
INSERT IMAGE   
### Commit that fixes this problem   
INSERT IMAGE   
### Reasoning:   
The bug in this program is that the program kept looking for a link inside the parentheses where there was one, and mistakenly recognized the inner parenthetical as a link. The symptom of this bug is that the inner parenthical was shown as a link rather than showing nothing. The failure inducing input shows this symptom of an incorrect output.   
