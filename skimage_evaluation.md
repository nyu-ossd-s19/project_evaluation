# Project Evaluation 



__Project Name:__ scikit-image


---

## Finding info about contributing on the website.

In the following section you should only enter the information that you
found on the project website. Some of the answers will be impossible to find, others
may be very hard to find. Do not _google_ for answers.

__Project website:__https://scikit-image.org/


__What is the purpose of the project:__ "scikit-image is a collection of algorithms for image processing."


__How easy was it to find information about contributing on the website?__ Very easy: Just click Community Guidelines on the homepage and navigate to the contributing link on that page.


__Contributing instructions:__ http://scikit-image.org/docs/stable/contribute.html

__URL for the code repository:__ https://github.com/scikit-image/scikit-image

__Bug/Issue tracker link:__ https://github.com/scikit-image/scikit-image/issues

__Mailing list:__ https://mail.python.org/mailman/listinfo/scikit-image

__Chat channel:__ https://skimage.zulipchat.com/

__Other communication channels:__ 

https://forum.image.sc/tags/scikit-image

https://stackoverflow.com/questions/tagged/scikit-image

---

## Finding info at the project repository and bug/issue tracker.

__License:__

Unless otherwise specified by LICENSE.txt files in individual
directories, all code is

Copyright (C) 2011, the scikit-image team
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in
    the documentation and/or other materials provided with the
    distribution.
 3. Neither the name of skimage nor the names of its contributors may be
    used to endorse or promote products derived from this software without
    specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT,
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING
IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

__Is it [OSI approved](https://opensource.org/licenses/alphabetical) license:__

Yes

__Programming Language:__

Python

__URL for contributing instructions:__ 

http://scikit-image.org/docs/stable/contribute.html

__Are the contributing instructions clear?__ 

Yes

__URL for code of conduct / community norms / community guildelines:__

https://scikit-image.org/community_guidelines.html

__URL for instructions for users to download and install the package:__


https://scikit-image.org/download.html

__Are these instructions clear? Do you think they would be easy to follow?__

Yes, very clear, utilizing pip and conda install(s)

__Number of contributors:__

1,256


__Usernames of three contributors with largest number of commits; for
each of them list the link to their latest commit__:

1. amuller https://github.com/scikit-learn/scikit-learn/pull/12639
2. ogrisel https://github.com/scikit-learn/scikit-learn/pull/12661
3. GaelVaroquaux https://github.com/scikit-learn/scikit-learn/pull/12894


__Number of commits:__

23,668

__Latest commit__

Feb 20th, 2019

- __link to the commit:__

https://github.com/scikit-learn/scikit-learn/commit/6649059d5ff74e94b8f6245817fa9b0f77d7f951

- __who made that commit:__

jeremiedbb

- __what type of work was commited?__ (was it a fix to a bug, implementation of a new feature, ...)

[MRG] MAINT: Continue moving from CBLAS to scipy cython blas

__Issues__

- __how many open issues are there:__

1,226

    - __url for the last issue created:__

https://github.com/scikit-learn/scikit-learn/issues/13202

    - __how many users discuss the issue:__

2
    
    - __when was the issue reported:__

6 hours ago (Feb 20th, 2019
    

- __how many closed issues are there:__

4,684

    - __url for the last issue closed:__

https://github.com/scikit-learn/scikit-learn/issues/13194

    - __how many users discussed the issue:__

3

    - __when was the issue reported:__

Feb 19th, 2019

    - __when was the issue closed:__

Feb 20th, 2019

- __how active is the discussion on the issues:__ 

Very active 

    - __example of a lot of good discussion:__ 

This could be an option if #12774 will be solved by removing empty bins in every case. I'm not sure if this should be optional behaviour or not. I stumbled upon some strange edge cases when trying to do that similar to #13165, but better discuss it there.

I've tested this on QuantileTransformer with the toy data from above. Resulting quantiles_ are indeed monotonic with n_quantiles=11, but the transform method seems to handle it well anyway and gives the expected result.
    
    - __example of an issue that does not have much discussion:__

Faster PolynomialFeatures https://github.com/scikit-learn/scikit-learn/issues/13173


- __are there issues marked "good for newbies", "beginner" or some other indicators that imply that they are good for beginner contributors:__ Yes. They are called "good first issue"

    - __how many of such issues are there?__ 8 Open, 44 Closed
    
    - __look at a few of them, do they look beginner friendly?__ Yes, mainly documentation synax/semantics



- __are there issues marked "documentation" or some other indicators that imply that they are documentation (user or developer specific):__ Yes

    - __how many of such issues are there?__ 27 Open, 59 Closed
    
    - __look at a few of them, do you think you could submit a fix?__ Yes, some are marked "good first issue"



__Pull requests__

- __how many open pull requests are there:__ 166

    - __url for the last pull request created:__ https://github.com/scikit-image/scikit-image/pull/3760
    
    - __when was the last pull request made:__ Feb 20th, 2019

    - __url for the oldest pull request created:__  https://github.com/scikit-image/scikit-image/pull/1
    
    - __when was the oldest pull request made:__ Jul 10th, 2011

- __how many closed pull requests are there:__ 2209

    - __url for the last pull request closed:__ Feb 20th, 2019
    
    - __how many users discussed the pull request:__ 3
    
    - __when was the pull request made:__ Feb 20th, 2019
    
    - __when was the pull request closed:__ Feb 20th, 2019
    

- __do maintainers respond quickly to pull requests when they are opened?__ Yes, this PR was reviewed and approved in one hour





---


## Summary assesment
__How friendly is this project for beginner contributors?__ It appears friendly since there is a "good first issue" tag, the devs are nice, and they also offer mentoring for those that aren't familiar with Python. I find that point alone exceptional


__Do the maintainers respond helpfully to questions in issues?__ Yes. Everyone appears friendly and turnaround time is very quick, about one hour.


__Are people friendly in the issues, discussion forum, and chat (for example, IRC or Slack)?__ Yes



__Do pull requests get reviewed?__ Yes, both manually and with automatic tests, from what I can tell.



__Do maintainers thank people for their contributions?__ Yes :)



