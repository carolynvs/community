# Help Wanted

Items marked with the `help wanted` label need to ensure that they are:

- Sufficiently actionable: clear description of what should be done
- Tractable for new/casual contributors: there is documentation how that type of change should be made
- Goldilocks priority: Not too high that a core contributor should do it, but not too low that it isn't useful enough for a core contributor to spend time to review it, answer questions, help get it into a release, etc.
- Up to date: Often these issues become obsolete and have already been done, are no longer desirable, no longer make sense, change in priority, change in difficulty, etc.

Related commands:

- `/help` : adds the `help wanted` label to an issue
- `/remove-help` : removes the `help wanted` label from an issue

# Good First Issue

Items marked with the `good first issue` label are intended for _new contributors_.
These make it clear to new contributors that they are welcome, valued, and provide
a clear starting point for joining the project. After a contributor has successfully
completed 1-2 `good first issue`'s, they should be ready to move on to `help wanted` items, saving remaining `good first issue`'s for other new contributors.

Please keep an eye out for pull requests from new contributors and help
move it through our processes. New contributors shouldn't be left to decipher prow
commands, build flakes, find an approver, or ping for reviews.

These items need to ensure that they follow the guidelines for `help wanted` labels (above)
in addition to meeting the following criteria:

- **Low Barrier to Entry**<br/>
  The task is something that a new contributor can tackle without
  advanced setup, or domain knowledge.
- **Clear Task**<br/>
  The task is agreed upon and does not require further discussions
  in the community. The recommended solution is clearly described in the issue and
  is limited in scope so that no unexpected changes arise during review.
- **Provides Context**<br/>
  If background knowledge is required, this should be explicitly mentioned
  and a list of suggested readings included.
- **Gives Examples**<br/>
  Link to examples of similar implementations so new contributors have a reference guide
  for their changes.
- **Identifies Relevant Code**<br/>
  The relevant code and tests should be linked in the issue.
- **Ready to Test**<br/>
  There should be existing tests that can be modified, or existing test
  cases fit to be copied. If the area of code doesn't have tests, before labeling the issue,
  add a test fixture. This prep often makes a great `help wanted` task!

## Suggestions

Provide extra assistance during reviews on `good first issue` pull requests:
- Answer questions and identify useful docs.
- Offer advice such as _"One way to reproduce this in a cluster is to do X and then you can use kubectl to   
  poke around"_, or _"Did you know that you can use fake clients to setup and test this easier?"_.
- Help new contributors learn enough about the project, setting up their environment,
  running tests, and navigating this area of the code so that they can tackle a
  related `help wanted` issue next time.

If you make someone feel like a part of our community, that it's safe to ask questions,
that people will let them know the rules/norms, that their contributions are helpful and appreciated... they will stick around! 🌈
- Encourage new contributors to seek help on the appropriate slack channels, introduce them, and include them in your conversations.
- Invite them to the SIG meetings.
- Give credit to new contributors so that others get to know them, _"Hey, would someone help give a second LGTM on @newperon's first PR on chocolate bunnies?"_. Mention them in the SIG channel/meeting, thank them on twitter or #shoutout.
- Use all the emoji in your approve or lgtm comment. 💖 🚀
- Let them know that their `good first issue` is getting extra attention to make the
  first one easier and help them find a follow-up issue.
- Suggest a related `help wanted` so that can build up experience in an area.
- People are more likely to continue contributing when they know what to expect,
  what's the acceptable way to ask for people to review a PR, nudge things along
  when a PR is stalled. Show them how we operate by helping move their first PR along.
- If you have time, let the contributor know that they can DM you with questions that
  they aren't yet comfortable asking the wider group.
