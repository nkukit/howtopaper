# Some rules to follow when writing a paper...

...in collaboration with me :-).

Welcome! It seems you are writing a paper with me! Over the years, I gained some experiences on what constitutes a good paper. I tried to put them together here, which will make your life (and mine ;-) hopefully easier.

## General Writing and Flow

- Don't forget the [reader](https://cseweb.ucsd.edu/~swanson/papers/science-of-writing.pdf). Make sure, you take his/her hand and guide him/her clearly through your thoughts and storyline.
- This is ESPECIALLY important for the abstract and introduction. Nick Berente has a good guideline for that:

<p align="center">
    <img src="https://github.com/nkukit/howtopaper/blob/master/image.png" alt="Intro">
  </a><br/>
</p>

- A scientific paper doesn't mean it takes rocket science to read it. Make it as easy as possible for the reader. Use short sentences, refrain from complicated sentence constructs (like you would do in German).
- Make sure you have a clear flow through your paper in general, but also each chapter in specific. What is the goal of each chapter, how does it contribute to the larger story you are trying to tell?
- Examples: Use examples whereever possible to illustrate your statements for the reader. If your paper has one main use case (e.g. application of image mining in the machining industry ;-)) always prefer using this example in each step of your argumentation. Don't switch use cases too often, e.g. medicine - manufacturing - traffic --> <em>Your</em> use case should "shine through" as often as possible.

<p align="center">
    <img src="https://media.giphy.com/media/ie76dJeem4xBDcf83e/giphy.gif" alt="Hi Thanos">
  </a><br/>
</p>

- Your paper will be shortened drastically in the writing and review process. It is inevitable (just as Thanos). Don't take it too hard and don't throw anything away, but either comment it out or use a "trash.tex" file, where you collect unused paragraphs.
- Refrain from using too many iterations like "First....Second....Third". It's okay to do this a few times, but it is lazy writing.
- Do not go below subsections (e.g. subsubsection), a 1.2.1 or 1.2.2.3 looks strange in a 20 page paper.
- Only use numbered subsections if there are at least three of them. In case of two topics: describe in the beginning of the section what you will present in the two paragraphs but do not number them as subsections.
- Figure and table captions should be self-containing. Make sure your caption does a good job on describing what the figure shows.
- Once you are done writing, the "editing" part starts. My best tip here is (as it is hard to correct one own's writing): Edit back to front (!!), paragraph by paragraph (NOT chapter by chapter). This typically works very well to get an outside perspective of your own work.

## Wording
<p align="center">
    <img src="https://media.giphy.com/media/SQgEr5ViRcXYs/giphy.gif" alt="Yoda">
  </a><br/>
</p>
- Use phrases like "this research aims to..." cautiously. Either you do something or you do not.
- Use "that" without preceeding comma if the following information is essential for understanding the sentence. Use ", which" in case the following information is nonessential.
- Always use "because" instead of "since" to avoid ambiguity
- Refrain from writing phrases like "we test this". Be more specific: "we test this relationship."

## Terminology

- Always call the same things with the same term. E.g, if your central contribution is an <em>artifact</em>, always call it "artifact" (not software tool, not model, not anything else). Decide on what term fits your idea best and then stick to it. This is really important!
- Use abbreviations consistently. If you introduced "machine learning (ML)", then it is always called "ML" from that point on. However, this does not apply to Abstract, Introduction and Conclusion, where no abbreviations should be used.

## References

- Try to use references only if you are either writing a statement which needs proof (nothing trivial) or you are naming examples. Try to use one core reference only for a statement, which is not too controversial. Only use multiple references when making examples or stating something controversial / provocative.
- Use page references only if you are directly citing
- Talking about references: Try to prefer sources from the same community / the top journals within this community. If you are submitting to a top journal, make sure to prefer sources from this very journal. Try to avoid self-referencing...at least until your manuscript gets accepted ;-)

## Grammar and TeX

- Use American English (AE).
- Try not to be colloquial (coll)—i.e., the complete opposite of this howto!
- Regarding tenses: You can either follow precicely [these](https://www.dropbox.com/s/d0s4dywiy8s25jd/A%20SHORT-CUT%20TO%20UNDERSTANDING%20TENSES_v3.doc?dl=0) rules for tenses. Or just use present tense throughout your whole paper. The decision is yours, there is nothing in between.
- Always use the package cleveref for cross-referencing of figues, chapters, tables, etc. with \Cref
- If you are referencing a precise figure/table/section, it is spelled in upper case, e.g. Figure 1 (use \Cref, not \cref)
- If your figure or table is on a different page than the cross-reference: Use \pageref
- The dash ('—') ('---' in LaTeX) has no spaces before or after.
- Do not use " for quotes in LaTeX, but `` and ''
- You can try to force a figure or table to a certain position by using 'htbp', e.g. \begin{figure}[htbp]

## Figures

- Use the same font for figures as you use in the body text. For LaTeX documents, this is mostly https://www.fontsquirrel.com/fonts/latin-modern-roman
- Always export figures as vector graphics, which are typically PDFs---This way you do not run into resolution issues
