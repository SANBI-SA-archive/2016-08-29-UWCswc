We recently hosted the first ever Software Carpentry event at the University
of the Western Cape (UWC). It was organised by Warren Jacobus and Peter van
Heusden, both from the South African National Bioinformatics Institute
(SANBI) and was advertised mostly within the Life Sciences and
Chemical Sciences buildings on campus (with some outreach to the
Institute for Wine Biotechnology at nearby Stellenbosch University). The
University of the Western Cape is situated near the geographic centre of
Cape Town, South Africa and originated as a college for people designated "Coloured"
during the Apartheid era.

At the final count we had a bit over 20 participants, drawn from departments
of biotechnology, earth sciences, engineering (from Cape Peninsula of
Technology, across the road from UWC), chemical sciences and of course
from SANBI itself. Our course focussed on the bash shell, git and Python
components of the Software Carpentry curriculum, with teaching done
by Michael Crusoe and Peter van Heusden, assisted by Warren Jacobus and
Carl Scheffler (from the company Takealot, who were interested in seeing
the Software Carpentry teaching methods).

The bash component unfortunately ran out of time, in part due to a slow start
caused by setup problems on the first day. We had assigned time the day before
to help people with install issues, but despite advertising this we only had
three people arrive for setup help and we had a number of thorny install problems
at the start of the workshop. In particular, the Anaconda Python distribution
failed to install on two Windows users' laptops, something we managed to
resolve in one case and worked around in the other case by providing a
training laptop.

We decided to split the Python teaching over two afternoons, using the
newer *gapminder* lesson. This lesson takes a more "bottom up" approach than
the older *inflammation* lesson, starting an introduction to variables and
type before moving on to modules and loops and then the use of
the `pandas` and `matplotlib` modules for working with and plotting
tabular data. The GDP dataset used is a real one, and offers more
opportunity for discussing the way graphs make patterns visible in the
data than is possible with the artificial *inflammation* dataset. The `pandas`
module is also a welcome update to methods of working with tabular data
compared to the `numpy` module used in the *inflammation* lesson.

For Python teaching Michael tried to move at a brisk pace in order to
illustrate some of the ways the skills learned could be applied to
problems the students would face in their research. During the teaching
time the helpers worked to keep the Etherpad updated with the commands being
used. Covering material rapidly left more time for exercises, a system
that worked fairly well, although it meant some students had to be 'caught up'
so that they could understand how to tackle the exercises. Even trying to
move through material fast, however, we did not manage to finish the Python
material, only getting as far as the plotting lesson.

Another problem we encountered was with Windows users and the *git* material.
Since the `nano` editor is no longer provided along with the *git bash*
distribution, Windows users were left with no 'default' editor to use with
their configuration. This meant that a commit without a `-m` flag
started the `vi` editor, a somewhat surprising experience for Windows
users. Luckily it turned out that the `notepad` editor on Windows can be
used as an editor alongside `git` and it is good enough for writing commit
messages. For other uses, we encouraged Windows users to install the *Atom*
editor.

Overall the workshop was a success and we ended off with Aurelia Moser
introducing the idea of Mozilla Science Study Groups. We will be starting
one on campus to help keep up momentum after the workshop, with an initial
focus on Python and then perhaps the Genomic Data Science content on Coursera.
Tweeting about Aurelia's input has revealed that there are others on campus
engaged in @MozLearn activities and we'll meet up soon to discuss collaboration!

We are planning on doing another Software Carpentry workshop at UWC next year
and in the meantime will be engaged with other (South) African Software
Carpentry activities.
