The Analytical Engine has no pretensions whatever to *originate* anything. It can do whatever we *know how to order it* to perform. It can *follow* analysis; but it has no power of *anticipating* any analytical relations or truths. Its province is to assist us in making available what we are already acquainted with.
> Ada Lovelace (1843), [*Sketch of the Analytical Engine, Note G*](https://web.archive.org/web/20250530031527/https://www.fourmilab.ch/babbage/sketch.html#:~:text=A.%20A.%20L.-,Note%20G,-It%20is%20desirable)


It was suggested tentatively that the question, "Can machines think?" should be replaced by "Are there imaginable digital computers which would do well in the imitation game?"
[...]
The original question, "Can machines think?" I believe to be too
meaningless to deserve discussion. Nevertheless I believe that at the end of the century
the use of words and general educated opinion will have altered so much that one will be
able to speak of machines thinking without expecting to be contradicted. I believe further
that no useful purpose is served by concealing these beliefs. The popular view that
scientists proceed inexorably from well-established fact to well-established fact, never
being influenced by any improved conjecture, is quite mistaken. Provided it is made clear
which are proved facts and which are conjectures, no harm can result. Conjectures are of
great importance since they suggest useful lines of research.
> Alan Turing (1950), [*Computing Machinery and Intelligence*](https://web.archive.org/web/20250530002831/https://courses.cs.umbc.edu/471/papers/turing.pdf)


The chess machine is an ideal one to start with, since: (1) the problem is sharply defined
both in allowed operations (the moves) and in the ultimate goal (checkmate); (2) it is
neither so simple as to be trivial nor too difficult for satisfactory solution; (3) chess is
generally considered to require "thinking" for skilful play; a solution of this problem will
force us either to admit the possibility of a mechanized thinking or to further restrict our
concept of "thinking"; (4) the discrete structure of chess fits well into the digital nature of
modern computers.
> Claude Shannon (1949), [Programming a Computer for Playing Chess](https://web.archive.org/web/20250519075435/https://vision.unipv.it/IA1/ProgrammingaComputerforPlayingChess.pdf)


We propose that a 2-month, 10-man study of artificial intelligence be carried out during the summer of 1956 at Dartmouth College in Hanover, New Hampshire. The study is to proceed on the basis of the conjecture that every aspect of learning or any other feature of intelligence can in principle be so precisely described that a machine can be made to simulate it. An attempt will be made to find how to make machines use language, form abstractions and concepts, solve kinds of problems now reserved for humans, and improve themselves.
> John McCarthy et al, [*Dartmouth Workshop Proposal*](https://web.archive.org/web/20250528124924/https://raysolomonoff.com/dartmouth/boxa/dart564props.pdf)


Programming computers to learn from experience should eventually eliminate the need for much of this detailed programming effort.
> Arthur Samuel (1959), [*Some Studies in Machine Learning Using the Game of Checkers*](https://web.archive.org/web/20250328090837/https://people.csail.mit.edu/brooks/idocs/Samuel.pdf)


 If we
 use, to achieve our purposes, a mechanical agency with whose operation
 we cannot efficiently interfere once we
 have started it, because the action is so
 fast and irrevocable that we have not
 the data to intervene before the action
 is complete, then we had better be
 quite sure that the purpose put into the
 machine is the purpose which we really
 desire and not merely a colorful imita-
 tion of it
> Norbert Wiener (1960), [*Some Moral and Technical Consequences of Automation*](https://web.archive.org/web/20250000000000*/https://www.cs.umd.edu/users/gasarch/BLOGPAPERS/moral.pdf)


Let an ultraintelligent machine be defined as a machine that can far surpass all the intellectual activities of any man however clever. Since the design of machines is one of these intellectual activities, an ultra-intelligent machine could design even better machines; there would then unquestionably be an "intelligence explosion," and the intelligence of man would be left far behind (see for example refs. [22], [34], [44]). Thus the first ultraintelligent machine is the last invention that man need ever make, provided that the machine is docile enough to tell us how to keep it under control. It is curious that this point is made so seldom outside of science fiction. It is sometimes worthwhile to take science fiction seriously.
> I.J. Good (1965), [*Speculations Concerning the First Ultraintelligent Machine*](https://web.archive.org/web/20010527181244/http://www.aeiveos.com/~bradbury/Authors/Computing/Good-IJ/SCtFUM.html)


Encoded in the large, highly evolved sensory and motor portions of the human brain is a billion years of experience about the nature of the world and how to survive in it. The deliberate process we call reasoning is, I believe, the thinnest veneer of human thought, effective only because it is supported by this much older and much more powerful, though usually unconscious, sensorimotor knowledge. We are all prodigious olympians in perceptual and motor areas, so good that we make the difficult look easy. Abstract thought, though, is a new trick, perhaps less than 100 thousand years old. We have not yet mastered it. It is not all that intrinsically difficult; it just seems so when we do it.
> Hans Moravec (1988), *Mind Children: The Future of Robot and Human Intelligence*  


This compression contest is motivated by the fact that being able to compress well is closely related to acting intelligently. In order to compress data, one has to find regularities in them, which is intrinsically difficult (many researchers live from analyzing data and finding compact models). So compressors beating the current "dumb" compressors need to be smart(er). Since the prize wants to stimulate developing "universally" smart compressors, we need a "universal" corpus of data. Arguably the online lexicon Wikipedia is a good snapshot of the Human World Knowledge. So the ultimate compressor of it should "understand" all human knowledge, i.e. be really smart. enwik8 is a hopefully representative 100MB extract from Wikipedia.
> Marcus Hutter (2006), [*The Hutter Prize*](https://web.archive.org/web/20060821073034/http://prize.hutter1.net/)


One thing that should be learned from the bitter lesson is the great power of general purpose methods, of methods that continue to scale with increased computation even as the available computation becomes very great. The two methods that seem to scale arbitrarily in this way are search and learning.

The second general point to be learned from the bitter lesson is that the actual contents of minds are tremendously, irredeemably complex; we should stop trying to find simple ways to think about the contents of minds, such as simple ways to think about space, objects, multiple agents, or symmetries. All these are part of the arbitrary, intrinsically-complex, outside world. They are not what should be built in, as their complexity is endless; instead we should build in only the meta-methods that can find and capture this arbitrary complexity. Essential to these methods is that they can find good approximations, but the search for them should be by our methods, not by us. We want AI agents that can discover like we can, not which contain what we have discovered. Building in our discoveries only makes it harder to see how the discovering process can be done.
> Rich Sutton, (2019), [*The Bitter Lesson*](https://web.archive.org/web/20250501195604/http://www.incompleteideas.net/IncIdeas/BitterLesson.html)


The strong scaling hypothesis is that, once we find a scalable architecture like self-attention or convolutions, which like the brain can be applied fairly uniformly (eg. “The Brain as a Universal Learning Machine”⁠ or Hawkins), we can simply train ever larger NNs and ever more sophisticated behavior will emerge naturally as the easiest way to optimize for all the tasks & data. More powerful NNs are ‘just’ scaled-up weak NNs, in much the same way that human brains look much like scaled-up primate brains⁠.
 
 While I was highly skeptical of scaling hypothesis advocates when I first became interested in AI 2004-2010 (back when AI was stuck in the doldrums of hopelessly narrow tools and dates like 2028 seemed impossibly far away), which smacked of numerology and “if you build it they will come” logic (at the time, we certainly didn’t have general algorithms that you could just throw compute at), in 2020, I have to admit, I was wrong and they were right. We built the compute, and the algorithms did come, and the scaling hypothesis has only looked more and more plausible every year since 2010.

> Gwern Branwen, (2022), [*The Scaling Hypothesis*](https://archive.is/F8fpB#scaling-hypothesis)


What this manifests as is – trained on the same dataset for long enough, pretty much every model with enough weights and training time converges to the same point. Sufficiently large diffusion conv-unets produce the same images as ViT generators. AR sampling produces the same images as diffusion.

This is a surprising observation! It implies that model behavior is not determined by architecture, hyperparameters, or optimizer choices. It’s determined by your dataset, nothing else. Everything else is a means to an end in efficiently delivery compute to approximating that dataset.

Then, when you refer to “Lambda”, “ChatGPT”, “Bard”, or “Claude” then, it’s not the model weights that you are referring to. It’s the dataset.
> James Betker (2023), [*The “it” in AI models is the dataset.*](https://web.archive.org/web/20250324194221/https://nonint.com/2023/06/10/the-it-in-ai-models-is-the-dataset/)
