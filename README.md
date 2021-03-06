# The Need For Freedom

Pull requests are automatically merged.

This is the beginning of an evidence sharing app to help those human
trafficking victims who can make use of it.  Please contribute a little,
anything you can find to add.  A typo, a worry opened as an issue, a link to a
resource.  Anything.

Work is in the 'devlog' branch.

# Current goals

- [ ] make a working cross-platform application using any backend, that can access the microphone
- [ ] communicate with the Haven project to see whether they have interest in immutable streamed recording.  https://github.com/guardianproject/haven/issues/431

# Explanation
 
When in a highly coercive situation, ones' resources to reach out may be taken
in collaboration with other complicit and coerced folks throughout society.  Even if
a recording of evidence is made, the recording may be found and deleted, and alternate
stories may instead be spread to cover up what really happened or is happening.

I have been struggling to start this work for years, and so far I have been able
to put this much in, which is almost nothing.  I think, still, it is enough to finish.

# Plan

We want to find a path to coding this that takes little developer effort, so as
to reach the goal[s].  We need to make this easy, record how to continue for
others to help effectively, keep ourselves safe, and find ways to keep going if
the project's progress becomes threatened.

# Design Proposals

These are all up for discussion.

* Storage
  * BSV blockchain  
    Already provides for strong immutable storage, cheap enough for audio.  Funding could be donated for now.   
    Concerns: existing nodejs libraries are central-proxy-based [meaning proxy can be coerced], but do upload to the real blockchain which can be verified via alternate channels.  If network censorship to proxies is an issue, it could possibly be reduced via use of Tor.
* Development backend:
  * Presently considering phonegap or kivy due to widespread community
    use and simplifying infrastructure.  The 'Haven' project exists already in Java,
    but some relation might be needed with them to reach these goals in
    ways likely to complete quickly.  They are also android-only, whereas phonegap
    and kivy are both android and ios.

# Priorities

1. Live audio recordings uploaded to blockchain, paid for by an open fund. 
   This is missing from freedom resources and is the primary goal of this
   effort.

2. Stealth recording.  Also important.

3. Optional public display of recordings.  
   Important for those areas without somebody to reach out to.

4. Forking BSV or another blockchain so as to provide unlimited free storage by using storage of community data as proof of work.

# Coda

If you've gotten to this point reading, please find a way for work to be
contributed to the project.
