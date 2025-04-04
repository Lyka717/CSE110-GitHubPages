# Context and Problem
_(Following is an excerpt from my group's proposal document)_

With thousands of active users on social media daily, automatic content
moderation has been the preferred method to tackle the constant stream of user
uploads that would be stressful on a human moderator. Content moderation
systems improve trust and safety in online platforms by flagging content that is
considered inappropriate or hateful based on community guidelines. However,
using automated systems to review human-made content also comes with false-
positive flagging and subsequent unfair banning, or punishment, of the content
itself. This confuses users, as victims of this mistake, as they can only see the
result or consequence (content flagging/account termination) with near to no
explanation of exactly why their content got punished. So what is a convenient
way for users to better understand how their content is moderated? But first,
we need to understand why users are confused.\
Within this lack of understanding of how their platform’s content moderation
systems works, users can get their posts flagged down and thus become more
speculative of the platform itself. One of the major flaws of content moderation
is that it can target some communities more often than others. For instance, the
LGBTQ+ and Black communities are some of the most impacted communities
from being targeted more specifically[6]. As shown in prior work the dataset
showed transgender and black people tended to be affected by content removal
even while following site guidelines. Thus leading people to speculate discrimi-
nation and prejudice behind the content moderation system or the social media
platform itself.

In addition to this speculation, users adapted to finding a workaround for
these content moderation systems to avoid unjustified punishments for their
content altogether. Another flaw of these algorithms is their inability to prop-
erly understand context and adapt to slang. Many moderation algorithms use
Large Language Models (LLMs)[7] to compare speech to lists of offensive or
inappropriate topics. Not only is this system prone to false positives due to lack
of context consideration, but it is also not a concept or warning explicitly given
to the user as common knowledge. This garners more speculation and results in
users’ usage of algospeak (a coded language using symbols or emojis to depict
certain letters, including inappropriate references), as a
workaround to avoid unjust punishment from automated moderation systems
altogether. For instance, many participants in [9] argued that after using algos-
peak, they have experienced less content moderation consequences. Overall, for
users to use this language in the first place is due to users’ lack of understanding
of how content moderation particularly works, and thus using algospeak as a
trial-and-error method of what makes the moderation system ”happy” to not
face the consequence of being flagged.

Moreover, many moderation systems struggle to understand different ac-
cents. Automatic Speech Recognition Systems (ASRs) are systems used to rec-
ognize speech to convert it into text or perform other tasks with them. These
use different machine learning algorithms and are trained on specific datasets.
These datasets tend to be biased towards native English speakers and do not
produce the most accurate results with people with different accents. Studies
have shown that the error rates produced by different ASRs for black people are
almost twice those that are produced by white people [4]. This shows that these
systems tend to be biased due to the biases already in their training datasets.

Research has also shown that these ASRs also perform worse for speakers born
outside North Atlantic Treaty Organization (NATO) countries [5].
With the issues detailed above, it is clear that moderation systems can mis-
takenly flag harmless content as inappropriate, causing disruption, distrust, and
dislike among users who are not told exactly why and how their content is
checked and processed in the social media platform. During such instances,
users are often frustrated as they are unaware of why their content contradicts
the social media platform’s guidelines. Thus resulting in, as explained by Myers-
West, users beginning to develop their own theories of how these systems work
[8]. For instance, users often assume that a specific person or unknown group
has purposefully flagged a post because of their personal opinions regarding the
user or the user’s content. Similarly, when the flagged content is related to pol-
itics, users assume that the platform’s management has hidden goals to protect
a certain political figure. Thus, many users develop theories relating to human
sources and are unaware that technological sources such as content moderation
algorithms are also responsible for their experiences with content moderation.
Some of the only sources that educate users about why their content might
be flagged are research papers, media coverage, and the community guidelines[9]
on social media platforms. This requires people to read through long documents
where they need to explicitly look for the policies on different community guide-
lines or read research papers that may be too technical. To our knowledge there
are not many easy-to-use tools that educate people about content moderation
systems and their flaws.

Our goal is to educate people, through interactive methods, about how con-
tent moderation systems work and the potential flaws in these systems. We
want to achieve this by implementing filters on platforms like Tiktok and In-
stagram that takes users’ audio input and then outputs information on whether
or not their statements may cause a content moderation system to flag their
content along with reasons for why their audio may be flagged. With this, users
can experiment with the filter to better understand how content moderation
systems work and the flaws of these systems. We believe this could help the
content moderation developers understand when they are being too harsh and
also help them understand the problems with their content moderation systems.
It could help content creators curate better content that will not get flagged.

- [6]  O. Haimson, D. Delmonaco, P. Nie, and A. Wegner. Disproportionate removals and differing content moderation experiences for conservative, transgender, and black social media users: Marginalization and moderation gray areas. Proceedings of the ACM on Human-Computer Interaction, 4, 2021.
- [7] Tao Huang. Content moderation by llm: From accuracy to legitimacy. 2024.
- [8] S. Myers West. Censored, suspended, shadowbanned: User interpretations of content moderation on social media platforms. New Media Society, 20(11),2018
- [9] E. Steen, K. Yurechko, and D. Klug. You can (not) say what you want: Using algospeak to contest and evade algorithmic content moderation on tiktok. Social Media +Society, 9(3), 2023.
