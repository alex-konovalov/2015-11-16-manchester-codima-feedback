# 2015-11-16-manchester-codima-feedback

This the text from the sticky notes, without alterations.

## Monday morning session: Shell lesson, instructor Kwasi Kwakwa

### Green notes:

* Good that you're going at the speed of the least experienced person in the room

* Friendly athmosphere :)

* Everyone had a chance to keep up

* Useful reminder of command prompt. The exercise with four possible answers
is good

* Thank you so much, it was great. However we need to be a bit more quick to
catch up other material such as pipes, filters, ...

* Learnt lots of new commands and shortcuts

* I enjoyed <non-readable word> this lecture on learning unix/shell

* Good enough: informative, valuable

* Clear and straightforward

* Learnt: pwd, mkdir, ls, deleting files and dir. Well done!

* Live coding great; Friendly; Signal system of sticky notes great

* Speed was good for most of it. Comfortable with taught topics

* Things make sense now!! :)

* Good. All my questions clearly answered - even on Twitter!

* Learning commands from scratch was very useful.

* Overall good and clear. I really understand what I came for


### Red notes:

* More setup time/smoother setup? Started a bit late =) (_written on green, though_)

* Pace was a little too slow for me

* Last exercise was a bit confusing at first

* More exercises would be Useful

* Please allow more time for writing longer commands, e.g. when
`nano ....txt` was introduced.

* nothing in particular!

* You need to be have time before start

* Could have been covered much more quickly

* Pace was very slow. Some participants seemed to spend a lot of time waiting

* Need more practice to know what directory I'm actually in

* Too fast in writing could not catch you and was stuck most of the time

* To improve: could have done `cd ..` earlier as people might get lost
going down file structure

* Ensure screens working before start. Would like to see the thesis that
caused all this trauma

* Perhaps, it was too easy, but I don't know about the experience of
others. I just expected something about bash - scripts, etc.


## Monday afternoon session: Make lesson, instructor Leighton Pritchard

### Green notes:

* Great! Thank you very much

* It was very good and useful

* Good

* Well explained + useful

* Very good. Well structured & paced

* Very well taught by the instructor - clear and easy to follow

* To improve: a bit fast at the end would have liked more tome to
understand `$(DAT_FILES)`

* good: really interesting + helpful answers to questions

* Make Quizzes work well!


### Red notes:

* To improve: a bit fast at the end would have liked more tome to
understand `$(DAT_FILES)` (_written on green, though_)

* Maybe a little fast (but this is probs more me being slow!)

* Python install should be suggested along with Git, GAP, etc.

* Probably would be better to avoid all mention of `*.dat`, or
just advise not to use it. It's just too much of a distraction.

* It seems like no one tested how `make` works on Windows.
Troubleshooting took a **long** time.


## Tuesday morning session: Git lesson, instructors Kwasi Kwakwa and Leighton Pritchard

### Green notes:

* It is great thanks a lot

* Terrific

* Straightforward and Interactive

* Twas fun; good teaching & communication skills; learnt how to do collaboration

* Very vell explained

* Good detail + I felt all my questions were answered

* Good: inspired me to use github

* This is GREEN. And well labeled so. Great user <unclear word> on GitHub

### Red notes:

* Please allow more time for longer commands

* Too much background noise to be able to fully concentrate on what the
speaker was saying

* Maybe it is a good idea to explain more the branches theory

* Sometimes went a bit fast. Maybe a better format is tutorial notes
online & Q and A in the room

* These are clearly PINK stickies! :) A lot of conversations during
lesson. Hard to hear.


## Tuesday afternoon session: GAP lesson, instructor Alexander Konovalov

I forgot to ask for stickies at the right moment and received only one green
note: "Overall session was excellent! Especially having some quiz meanwhile!".
But GAP lesson will be continued on Wednesday, so we will hopefully hear more.

I had one hour and covered the
[1st part of the lesson](http://alex-konovalov.github.io/gap-lesson/01-command-line.html)
almost completely. I had to shorten list operations just demonstrating them on
screen without typing, and also omit `WriteGapIniFile` which I have to show tomorrow
instead.

I've connected to a remote VM running Windows to show some customisations of the
shell, and that seemed to be useful. `SetHelpViewer("browser")` caused some problems
- while it was useful to be informed about them, for the 1st lesson it's better to
use the text-only help to ensure that the same output is seen on all operating
systems.

Another remark is that the instructor should start GAP with `-r` options or maybe
in a dedicated user account to avoid interfering with own GAP settings e.g.
locally installed packages and other content of `.gap` directory.

There were interesting questions on EtherPad at
http://pad.software-carpentry.org/2015-11-16-manchester-codima,
and questions arising in the audience were helped effectively by
Nick and Michael. There were two quizzes answered on EtherPad
(as Dima pointed out, the quesiton on `Filtered( Partitions(10), x -> 5 in x);`
could be formulated better) and one final challenge.


## Wednesday morning session: GAP lesson, instructor Alexander Konovalov

### Green notes:

* Examples great, well presented, good pace

* Good idea to teach attributes

* Good. I have learned new stuff!

* The lesson has so many examples. That is quite good.

* I found GAP sessions very useful! Fast paced, but manageable (any faster
  would be too fast)

* Was good to hear about advanced features like methods + attributes.

* Very well-explained.

* Thanks a lot we looking for more interesting stuff

* The GAP lecture was good. Useful to me (and old user) as I learnt few things
like the .tst file et cetera.

* Learning about attributes was helpful.

* Good: meaningful examples

* It was cool to be looking at a research style problem

* Lots of useful "good practise" stuff e.g. using functions + test files

* Debugging e.g. in functions was good to learn

* Good use of exercises

* Useful links about more efficient ways of doing things, manuals, etc.


### Red notes:

**Use of dual screens:**

* Would be good if the display was split screen so we could view the .g files
being edited in nano and what was going in the terminal at the same time.

* Jumping between the nano window and GAP window makes it hard to keep up.
Is it possible to have both displayed simultaneously?

* Multiple projector setup would be useful for code/GAP screens

* It would be good to have a 2nd screen showing <unclear word> commands.

**Pace of the lesson:**

* Sometimes it was hard to keep up with what was happening because
things were taken off the screen too quickly.

* Possible improvement: slightly slower pace when students are expected to
repeat the exercise. It is difficult to type in commands and listen to the
discussion at the same time.

* Quite fast-paced

* The pace was a bit fast compared for the first few days for someone
who has not used GAP before or programmed much in general. But I will manage
with the links to the manual and CoDiMa web links.

**Content of the lesson:**

* Would be good to hear about what GAP offers to someone interested in
computation but not specifically group theory.

* What about the algorithmic part? Maybe some well-known algorithms etc?

**Other:**

* Main parts would be helpful on board to refer to.

* More use of EtherPad, e.g. put scripts for functions on there

* Perhaps the files we write could be available online in case someone
falls behind or is slow at typing

* Too many feedback requests!!!

## Remarks on the GAP lesson (AK)

This was a beta-testing of the lesson on GAP, which I have started to develop
under the EPSRC-funded CoDiMa project. I was inspired by other lessons, in
particular shell and Python lesson, and built a story around a research like
problem, showing how a GAP beginner (possibly a 1st year PhD student in algebra)
could look for the necessary information in the system and build up their
skills from working with command line to writing scripts, organising code into
functions, using regression tests and using GAP as a tool to find examples and
counterexamples.

The content seemed to be well received - most of the red stickies are related to
the pace of the lesson and the lack of the 2nd screen, but not to the content.
The next step is to polish the beta-version of the lesson in a more collaborative
way, and attendees were invited to practice their Git+GitHub skills by helping to
improve the lesson and submit new issues and pull requests at
https://github.com/alex-konovalov/gap-lesson as a kind of a post-lesson support
that I can provide.

I agree with all feedback regarding the pace of the lesson. This was the 1st time
it is taught, and no previous timings were available. It happened that on Wednesday
I started a bit too fast and had some spare time at the end. I will take into
account that, and will also try to use EtherPad more proactively next time, and
also will not switch back and forth between screens so fast if I would be teaching
in a single projector mode (splitting screen horisontally or vertically is not a
very good option in this case, unless you can make the font smaller to fit more
text not losing readability). However, the links to download both files (which
are stored in the lesson's `code` directory) were posted on EtherPad prior to
the lesson.

For the record, I'v spent 1 hour on Tuesday to cover "First session with GAP"
and left "Some more GAP objects" for self-study. The rest ("Functions in GAP",
"Using regression tests", "Small groups search", "Attributes and Methods" and
then walking through http://alex-konovalov.github.io/gap-lesson/discussion.html
and helping to customise GAP with `WriteGapIniFile`) took 3 hours on Wednesday.

The lesson was not intended to cover the algorithmic part - that is planned to
be covered later in the school which runs for 5 days and is continued after the
Software Carpentry. The same is about what GAP offers to someone interested in
computation but not specifically group theory - we would like to teach practical
skills using which learners will be able to find themselves what GAP offers for
their field and explore this efficiently. They should be able to get more information
during the subsequent days of the school, for example at the "Bring your own problem"
session. In the future, the may be other lessons based around other problems and
intended for more advanced level.


## General remarks (AK):

* Next time, check that the Eventrbite form has a field for dietary
requirements. This time, we were asking to indicated them in a separate
email.

* Check if this is suggested somewhere in instructor's guide: how to
enter `#` sign on a British Mac keyboard?

* Next time, check that the whiteboard is both wide and not obstructed
by the screen. On Monday, it satisfied only the 1st of these two conditions.

* Suggestion for the debrief: instructions should not only tell how to
install the software, but also how to check that is has been installed
properly, e.g. starting the terminal and typing `git` or `make`. That
would help to avoid delays on Mondays.

* Idea for the future: Make lesson dependent on Python perfectly suites
workshops where Python is taught. I understand that it's a hard task to
maintain several lessons om Make automating different processes, but I
would be interested in having a version of this for the LaTeX paper
(with images, multiple files, data files that feed into the paper,
bibliography etc.)

* Interestingly, on Wednesday learners seemed to be surprised when I have
demonstrated how to find the 1st three lessons on the Software Carpentry
website. Should that be emphasized better ?

## General remarks (LP):

### Make

For future room setups:

* Are there enough power supplies for attendees to run laptops? We can't assume all turn up fully charged or will last the day. Having only one socket at the back could have been more serious if we didn't have Aleksandra as a local SSI representative.

* [Be Prepared!](http://members.scouts.org.uk/supportresources/761/promise-law-and-motto) Always carry spare cables! The room's SVGA cable was faulty and cast a yellow tone on everything. Happily, one of us had a spare (I've had similar issues at University of Dundee…)

* We weren't allowed to put up direction signs/advertising in the main building "due to Health and Safety" - co-ordination with the host site could clarify.

More generally:

* Agreed about Mac keyboards and the '#' symbol. This is a particular problem when using `Emacs`, as the key combination can have other meanings. Using `nano` means we don't have to think about it, but if someone insists on `Emacs` it could come up.

* I should have noticed the `Make` lessons were dependent on working Python, and realised that this ought to have been a requirement for pre-installation on the course page. That cost us around 20min of the lesson. Next time I'll remember, but we should flag this up on the `make` lesson repo.

* The `make` installation fail was out of our hands, but insisting that students check that their copy of `make` works before the course could possibly flag up issues ahead of time. We lost quite a bit of the lesson to this, and it was disruptive. Again, it's a consideration we could bring up on the lesson repo.

* As the `make` lesson doesn't *need* to depend on Python (or any other complex installation), but does need to depend on the shell, maybe a shell script would be a better choice for the example than a Python script. I think that precompiled binaries wouldn't be practical, and that Perl/Java/whatever code would have similar dependency issues - shell seems to be the only requirement that stands out. It might make the visualisation step difficult, though - but there are ways to do ASCII horizontal bar graphs in the shell.

* I thought that in the `make` lesson I had to go into the audience as a helper a bit too often, and this was distracting from the flow (though it stopped me racing ahead, there were a couple of questions that were tangential to the topic: e.g. "How do I record my terminal input and output?", and which me addressing them would have disadvantaged the class - that's the kind of question a helper can answer via EtherPad)- 1/2 more available helpers would have been useful in the afternoon.

* A couple of points raised by helpers in the `make` session were to be covered later in the session. I realise the intent is to be helpful, but the extra cognitive load involved in flagging up items and concepts that will be discussed later, without actually discussing them, can be distracting. It also makes the flow a bit less smooth. That could be reduced if helpers were familiar with the running order of the lesson beforehand, and knew what was coming up later.

* Compared to other SWC workshops, the EtherPad was very lightly-used in Monday's session. I don't know if this is because the students didn't like it, or didn't find it useful, or weren't reminded of it. Previously it's been good for helpers to flag up other concepts to students, and for the students who are a bit ahead to see other relevant links out from the lesson, without getting into conversations and distracting others. Can we make more of the EtherPad?

=======
### Git

* I hadn't prepared as well for the Git lesson as for the Make lesson, and I think that showed, especially early on. After swapping over from Kwasi earlier in the course material than we intended, I took a while to get into my stride with the Ignoring Files/`.gitignore` section.

* I'm not sure switching instructors during Git is the best idea - I think that there's more potential for teaching slightly different mental models of how Git works, that way.

* I found that the noise levels in the classroom were problematic during the collaboration part of the session. I wasn't sure if this was because people were collaborating, chatting because they were already ahead, or whether there was something else going on. It took me a while to get everyone's attention on more than one occasion, and some of the noisy conversations weren't entirely course-related. One in particular was trying to sort out problems due to a non-standard setup (one student was logging in to a remote Linux server, which made for some problems)

* After the session, I considered that there's a lot of value to be had in setting up a collaboration scenario that runs consistently through the entire session, and is specific to the students' own interests, wherever possible. In this case, that could have been a LaTeX document collaboration (something I've done myself in Git).

* Though we didn't get as far as the Open Science section, the difference between the standard Mathematics publication/open peer review path and that described as 'default' is significant, and might make that lesson less relevant.

* We had an odd number of students, for which the natural way to cope is - I now think - for the instructor to pair up with the one left over. We tried having a group of three, and I tagged on with another pair to make a second group of three. That caused some confusion, as we (inevitably) ran into Git conflicts in practice earlier than was in the lesson plan.

* In the end, for Git I felt I was saved by the strength of the lesson plan. It carves a sound path through the central concepts, so it's hard to go too wrong as an instructor.

## General Remarks(KK):
* Note to self, check laptop beforehand and make sure that it still has a working VGA port. We lost a bit of time to that

* An unforseen consequence of having students pair up for the `git` section was them consulting each other and talking quite a bit. Not necessarily a bad thing, since we like peer learning, but it also got in the way of the lesson flow.

* Just to emphasize, make sure that there has been some thought put into powering all the laptops people will bring along. Also internet access. Luckily there were plans in place this time.

* `make` being broken in the most recent version of gitbash was unforseen, but still slowed down the class quite a bit and meant that some of the students did not get hands-on experience  

* The `shell` lesson went a lot slower than expected. Part of this was just me taking too long to warm up and get into the lesson and part of it was that some people seemed to be struggling with having a decent mental model for how to navigate directories via the command line. There seems to be an even split between people who liked the pace and people who didn't, so maybe my judgement of the pace wasn't too far off, but it still meant I left a lot of stuff undone. It might just be a consequence of the wide spread of abilities we had in the room
* The nice thing about a room full of mathematicians was that the idea of a version control system as a way to manipulate a graph of changes to a system seemed to go across reasonably well. That helped with the `git` session I thought.
