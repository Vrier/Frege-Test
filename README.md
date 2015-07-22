\documentclass{article}

\usepackage[T1]{fontenc}
\usepackage[english]{babel}

%\usepackage{fullpage}
%\usepackage{setspace}
%\doublespacing

\usepackage{natbib}

\usepackage{xcolor}
\newcommand{\todo}[1]{{\textcolor{red}{#1}}}
\newcommand{\done}[1]{{\textcolor{blue}{#1}}}

\usepackage{url,amsmath}

\title{Frege on Deflationism and Truth-Value Gaps}
\author{Sara L.\ Uckelman and Tom Stephen \\
Department of Philosophy, Durham University \\
\url{s.l.uckelman@durham.ac.uk},
\url{thomas.stephen@durham.ac.uk}}

\begin{document}

\maketitle

\section{Introduction}
The purpose of the present is to point out an inconsistency between two logico-semantic principles that Frege maintained:
\begin{equation}\label{tvg}
\text{Truth-value gaps.}
\end{equation}
\begin{equation}\label{dat}
\text{Deflationism about truth.}
\end{equation}
\todo{More specifically, we aim to show that these two views are attributable to Frege, and thus that Frege's views of language and truth are inconsistent.  From consideration of a specific example, we infer the general conclusion outlined above.}

\todo{We begin by locating (\ref{tvg}) and
(\ref{dat}) in Frege (\S\ref{non-refer} and \S\ref{deflate},
respectively).  Next, we show their inconsistency (\S\ref{problem}),
and then discuss Dummett's views on the matter, and show his
conclusions to be problematic (\S\ref{dummett}).  We conclude
(\S\ref{conclude}).}

\section{Truth-value gaps}\label{non-refer}
In this section, we show how Frege's commitments to the principle of compositionality and his views about what the sense and reference of a sentence are lead as a matter of consequence to the existence of truth-value gaps.  The argument proceeds in six steps. 


Frege introduces his famous distinction between sense and reference initially to account for how it is that proper names which pick out the same object in the world can nevertheless not be intersubstitutable, but he then extends the distinction to cover sentences, specifically ``whole declarative sentences'' \cite[p.~202]{frege-sr}.  Every sentence contains a proposition, and the question then is whether the proposition (thought) contained by a sentence should be ``regarded as the sense or the nominatum of the sentence'' \cite[p.~202]{frege-sr}.  Frege concludes that the thought cannot be the reference and thus it must be its sense.  This thought---the sense of the sentence---is
constructed compositionally:
\begin{quote}
If, then, we look upon thoughts as composed of simple parts, and take these, in turn, to correspond to the simple parts of sentences, we can understand how a few parts of sentences can go to make up a great multitude of sentences, to which, in turn, there correspond a great multitude of thoughts \cite[p.~1]{frege-ct}.
\end{quote}
These facts leads us to our first two premises:
\begin{equation}
\text{The sense of a sentence is composed of the senses of its parts.}
\end{equation}
and
\begin{equation}
\text{The reference of a sentence is determined by its sense.}
\end{equation}
If the thought contained in a sentence is its sense, and not its reference, then something else must be the reference for a sentence, and Frege argues that we must `accepted the \emph{truth-value} of a sentence as its nominatum'  \cite[p.~203]{frege-sr}, which is our third premise:
\begin{equation}
\text{The reference of a sentence is a truth-value.}
\end{equation}
The truth-value of a sentence is either `true' or `false'; `there are no other truth-values' \cite[p.~203]{frege-sr}.

The fourth premise indicates the relationship between the reference of the whole and the reference of the parts:
\begin{equation}\label{tv-det}
\text{A sentence's truth-value is determined by the references of the parts.}
\end{equation}
This follows from the fact that ``it is obviously the nominatum of [a] name to which the predicate is either ascribed or denied'' \cite[p.~202]{frege-sr}. If the ascribed predicate does in fact apply to the reference, the sentence is true, and false otherwise; similarly, if the denied predicate does in fact not apply to the reference, the sentence is true, and false otherwise.\footnote{In this respect, Frege is quite Aristotelian, in that ``To say of what is that it is not, or of what is not that it is, is false, while to say of what is that it is, and of what is not that it is not, is true'' \cite[Book IV, Part 7]{ari-met}.}  It follows from (\ref{tv-det}) that:
\begin{equation}
\text{If a part lacks a reference, then the truth-value of the sentence cannot be determined.}
\end{equation}
and therefore,
\begin{equation}\label{no-ref}
\text{If a part of a sentence lacks a reference, then the whole sentence has no reference, and hence has no truth value.}
\end{equation}
Frege explicitly notes that `It may in any case be expected that there are such sentences [with only sense and no nominatum], just as there are constituents of sentences which do have sense but no nominatum' \cite[p.~202]{frege-sr}.

\section{Frege on deflationism about truth}\label{deflate}
In this section we summarize Frege's views on deflationism about truth, focusing on the `equivalence principle' and how it fits in to his philosophy of language.

Deflationary theories of truth claim that there is nothing substantive to be said about the nature of truth. The concept of truth can be `deflated away' by reducing it to other terms, such that truth has no tangible role to play in our metaphysics or our language. A central, though not universal%citation, footnote, or further comment?
, tenet for deflationary theories is the `equivalence principle' which states that for any sentence $s$:
\begin{equation}\label{equivprinc}
\text{``}s\text{' is true' has the same meaning as }s.
\end{equation}
This principle provides a schema for removing the `is true' predicate from our sentences, in order to show that it contributes nothing substantive to the meaning of the sentence. 

Frege is commonly held to be among the earliest advocates of a deflationary theory of truth \cite{stanford-deflationary}, but some have argued that Frege should not be considered a deflationist because the concept of truth \emph{does} play a substantive role in his philosophy of language and logic\cite{heckmay}. Heck and May argue that since the nominatum of any declarative sentence (if it has one) is either the True or the False \cite[p.~203]{frege-sr}, and these truth-values are referents of sentences in the same way that objects can be the referents of words. They must `exist' in some real sense then for Frege, and thus cannot be simply deflated away.  Pardey argues that truth for Frege is something `so primitive and simple' that it cannot be reduced to anything more basic \cite[p.~228]{pardey}. 
Frege himself notes that `it would be futile to employ a definition in order to make it clearer what is to be understood by `true'\,' \cite{logic1897}.

Whether or not he is a deflationist, what is important is that he explicitly endorsed a form of the equivalence principle: 
\begin{quote}
It is worthy of notice that the sentence `I smell the scent of violets' has the same content as the sentence `it is true that I smell the scent of violets'. So it seems, then, that nothing is added to the thought by my ascribing to it the property of truth \cite[p.~293]{frege-thought}
\end{quote}
Similarly, he also says that:
\begin{quote}
One can indeed say: `The thought that 5 is a prime number is true'. But closer examination shows that nothing more has been said than in the simple sentence `5 is a prime number' \cite[p.~203]{frege-sr}
\end{quote}
Thus, Frege clearly believed the predicate `is true' is redundant; adding it does not change the sense of the sentence.  It is from his ascription to the equivalence principle (\ref{equivprinc}) that we can derive the problem from truth-value gaps.  For if the senses (the truth conditions) of the sentences are the same, then the reference (truth value/semantic content) must also be the same.

\section{The problem}\label{problem}
The problem that Frege faces is the following.  The sentence:
\begin{equation}\label{no-tv}
\text{Odysseus deeply asleep was disembarked at Ithaca.}
\end{equation}
has no truth-value (by \ref{no-ref}), because one of its parts (Odysseus) has no reference.  But then
\begin{equation}\label{false}
\text{`Odysseus deeply asleep was disembarked at Ithaca' is true}
\end{equation}
is false, because (\ref{no-tv}) has no truth value. From this it follows that 
\begin{equation}\label{conflict}
\text{(\ref{no-tv}) and (\ref{false}) don't have the same truth-value.}
\end{equation}
But (\ref{conflict}) violates the equivalence thesis (\ref{equivprinc}).

\section{Problems to address}

\subsection{The Falsity of \ref{false}}

Doesn't \ref{false} contain the same non-referring term, `Odysseus', as \ref{no-tv}? Shouldn't it therefore equally lack a truth value by \ref{no-ref}?



\ref{false} does not have a non-refering term
\done{He then counters my concern above about use/mention saying:
\begin{quote}It is impossible, even on Fregean
grounds, to argue that `It is true that $A$' will itself express a
thought that is neither true nor false, on the ground that it
contains, within the substantival clause, a name that lacks a bearer
(referent): for we are here taking the substantival clause to have an
oblique reference, so that the name will therefore stand for its
sense, which we assumed it had.\end{quote}
And similarly later:
\begin{quote}We have already noted that, if the
failure of A to be either true or false is due to the presence of a
name which lacks a bearer, we cannot on the same ground claim that
`It is true that $A$' fails to be either true or false: if we have
chosen to use the words `true' and 'false' in such a way that a
sentence may be neither true nor false only when it contains a name,
having a direct reference, which lacks a bearer, then nothing can
compel us to admit further reasons for calling other sentences
`neither true nor false'.\end{quote}
And he clearly endorses the Tarskian
meta-language object-language reading of the equivalence principle,
the one we use, when he talks, for example, of equating "'S is
true' with A, where S is the canonical name of A."}

\subsection{Frege on Fiction}

The sentence \ref{no-tv} is meant in a fictional context, can Frege escape the problem by claiming that all problematic sentences are ones `for which the question of truth does not arise'?


We also introduce a distinction that Frege
makes in these contexts between sentences which aim at truth and
those which do not; he thinks that this mitigates the problem of
non-referential sentences (due to non-referential terms in them), but
we shall show, in \S\ref{fic-error}, that the distinction does not partition the relevant cases in the way it needs to in order to serve
as a solution.




Though sentences such as ``Penelope is
Odysseus's wife'' come out to not have a truth-value on his account
of meaning, Frege does not view this as a problem.  He distinguishes
poetry and myth, on the one hand, from discourse that ``aims at
knowledge'', that is science or scientific discourse.  Because only
the latter is aimed at knowledge, in only the latter contexts does it
make sense to ask whether a sentence is true or false.  When we speak
about poetry and myth there are many questions we might wish to ask
or matters to consider---for example ``we are fascinated by the
euphony of the language and also by the sense of the sentences and by
the images and emotions evoked\dots whether the name `Odysseus' has a
nominatum is therefore immaterial to us as long as we accept the poem
as a work of art'' \cite[p.~203]{frege-sr}.  It is only when we go
beyond merely grasping a thought to the question of \emph{knowing} it
that truth-values come into play.
In \S\ref{non-refer}, we discussed how Frege
makes a distinction between assertions about poetry and myth and
assertions which have ``scientific use'', a distinction corresponding
to that between merely grasping a thought and actually knowing it. 
The division between poetry and truth is located in the intentions of
the speaker \todo{get carl cite};.

Unfortunately, this distinction does not
ultimately serve the purpose that Frege needs it to.  If it were
possible to demarcate sentences such that all those which have
non-referring terms are relegated to the realm of poetry, myth, or
fiction, then Frege could respond to our puzzle simply by saying that
the existence of truth-value gaps is not inconsistent with his
adherence to deflationism simply because assertions of poetry and the
like are not the sort of assertions that the predicates `true' or
`false' apply to.  But, unfortunately, we cannot demarcate sentences
in this way: Though Frege's examples of sentences with non-referring
terms are all drawn from the poetic realm, they need not be.  We can
find assertions in the realm of science or truth which contain
non-referring terms; but the fact that these terms do not in fact
refer is not known.  Regarding discourse with non-referring terms,
Crane makes a distinction between ``fiction'' and ``error'':
\emph{Error} occurs ``when we think about things which have been
genuinely supposed to exist, but do not'', while \emph{fiction}
happens ``when we think about things which we know do not exist''.
Though Crane frames the distinction in terms of ways we think about
things, it is easy to life the distinction to ways we \emph{talk}
about things, or more precisely, what sort of things we can talk
about, namely, error-objects and fictional-objects. 
Fictional-objects, then, occur in poetic and non-truth based
assertions where we don't intend what we are saying to be
truth-evaluable.  But when we do intend to assert something, and thus
to assert it as true, that has a term which doesn't refer, then we
have an error-object.   We may have intended our assertions about
phlogiston to be truth-evaluable, but because there is no such thing
as phlogiston, our intention alone is not sufficient to succeed in
making it so.

Thus, even if Frege has a solution to cases such
as ``Penelope is Odysseus's wife'', he still will face issues in
accounting for sentences such as ``Even dephlogisticated nitrous acid
contains some phlogiston, independent of that which is contained in
the fixed air and phlogisticated air, which are its constituent
parts'' \cite[p.104]{kirwan}.

The important point about both of these
distinctions is that they are intensional in nature: For Crane, the
division arises from whether or not we \emph{know} the things we are
talking about exist or not: If we do know they are non-existent, then
we are in the realm of fiction.  If we don't, we are in the realm of
error.

\section{Other people's take on the problem}

\subsection{The Well-known problem with Truth value gaps for Deflationary theories of Falsity}
Traditional problem of truth value gaps and deflationism
\subsection{Dummett: Philosophy of Language}

This apparent inconsistency between the equivalence principle and the possibility of truth-value gaps is not a new discovery \citep[\S 7.3]{stanford-deflationary}, yet few people have noticed this conflict occurs in Frege. In fact, Dummett is the only one we have found to have even touched upon the issue.  When discussing Frege's assent to the equivalence principle, he outlines our objection, framing it as a preliminary reservation against adopting the principle:
\begin{quote}Suppose that $A$ is a sentence which expresses a thought which may, in certain circumstances, be neither true nor false. Then the sentence `It is true that $A$' cannot be equivalent to $A$: for, when the thought expressed by $A$ is neither true nor false, say because $A$ contains a name which has a sense but lacks a bearer, the thought expressed by $A$ is not false \cite[p.~445]{f-pol}.\end{quote}

\done{He then goes on (somewhat tangentially in my opinion, as he has already shown that this is unnecessary to assuage the criticism in the previous paragraph) to argue that `There is, nevertheless, a clear truth underlying the claim that we must use a two-valued logic for the language in which we state the semantics of a language governed by a many-valued logic'}

\done{After this he, rather strangely, says
"Given this reservation, the equivalence thesis appears at least
plausible", without offering a counter argument to it or even
mentioning it again for the rest of the chapter.}

\section{Conclusion}\label{conclude}

Tom's comments:
\done{This problem isn't restricted to
non-referring terms (though that is precisely why it is a problem
specifically for Frege), but will be the case where ever we allow for
truth-value gaps. This might be concerning for in a much wider
context to deflationary theories in general, though I think it's
right to look at Frege specifically for someone who proposes both a
deflationary theory of truth and a truth gap theory of non-referring
names.}




\section{extra stuff}

Frege and the compositionality of meaning are so
closely associated that the Principle of Semantic
Compositionality---``the principle that the meaning of an expression
is a function of, and only of, the meaning of its parts together with
the method by which those parts are combined''---is often called
simply ``Frege's Principle''
\cite[p.~11]{pelletier}.\footnote{Nevertheless, there are those, such
as \cite{janssen}, who argue that Frege never quite adopted compositionality.}  The clearest account of Frege's compositionality can be  found in \cite{frege-ct}.

\todo{Tom: Do you think that in section 3.2 it
should be mentioned that in (7) ``'Odysseus's wife was Penelope' is
true'' might not be something that Frege had intended his
deflationism to cover, given the use/mention discussion we had
earlier? I think we both agreed that this would not be a good move
for Frege in the long run, but we can't really tell definitively from
the text that he means ``'Odysseus's wife was Penelope' is true''
rather than ``Odysseus's wife was Penelope is true'', which contains
a non-referring name and is hence truth-valueless.}




\todo{Frege's Thesis: ``If one component of a mathematical compound thought is replaced by another thought having the same truth-value, then the resultant compound thought has the same truth-value as the original'' \cite[p.~17]{frege-ct}.}

\todo{One might be tempted to regard the relation of the thought to Truth not as that of sense to reference, but rather as that of subject to predicate \cite[p.~203]{frege-sr}.}

\todo{Whatever it is for two sentences to have the same meaning, a minimal condition is that they have the same truth-values (cf. \cite[p.~298]{frege-thought}).}


\bibliographystyle{chicago}
\bibliography{frege}

\end{document}



