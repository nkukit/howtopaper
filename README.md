# Some rules to follow when writing a paper...

...at the Applied AI Lab.

Welcome! It seems you are writing a paper with my supervision. Congratulations! (Although, we will see if you think it was worth congratulating you on that decision at the end).

However, be sure to follow the following rules as it makes my life a whole lot easier!

<p align="center">
    <img src="https://media.giphy.com/media/3o7aTkjnoAzNaxPes8/giphy.gif" alt="Obey the rules!">
  </a><br/>
</p>

## General Writing and Flow

- Don't forget the [reader](https://cseweb.ucsd.edu/~swanson/papers/science-of-writing.pdf)
- A scientific paper doesn't mean it takes rocket science to read it. Make it as easy as possible for the reader. Use short sentences, refrain from complicated sentence constructs (like you would do in German).
- Make sure you have a clear flow through your paper in general, but also each chapter in specific.
- Examples: Use examples whereever possible to illustrate your statements for the reader. If your paper has one main use case (e.g. application of image mining in the machining industry ;-)) always prefer using this example in each step of your argumentation. Don't switch use cases too often, e.g. medicine - manufacturing - traffic --> <em>Your</em> use case should "shine through" as often as possible.

<p align="center">
    <img src="https://media.giphy.com/media/ie76dJeem4xBDcf83e/giphy.gif" alt="Hi Thanos">
  </a><br/>
</p>

- Your paper will be shortened drastically in the writing and review process. It is inevitable (just as Thanos). Don't take it too hard and don't throw anything away, but either comment it out or use a "trash.tex" file, where you collect unused paragraphs.
- Refrain from using too many iterations like "First....Second....Third". It's okay to do this a few times, but it is lazy writing.
- Do not go below subsections (e.g. subsubsection), a 1.2.1 or 1.2.2.3 looks strange in a 20 page paper.

## Terminology

- Always call the same things with the same term. E.g, if your central contribution is an <em>artifact</em>, always call it "artifact" (not software tool, not model, not anything else). Decide on what term fits your idea best and then stick to it.
- Use abbreviations consistently. If you introduced "machine learning (ML)", then it is always called "ML" from that point on. However, this does not apply to Abstract, Introduction and Conclusion, where no abbreviations should be used.

## References

- Try to use references only if you are either writing a statement which needs proof (nothing trivial) or you are naming examples. Try to use one core reference only for a statement, which is not too controversial. Only use multiple references when making examples or stating something controversial / provocative.
- Use page references only if you are directly citing
- Talking about references: Try to prefer sources from the same community / the top journals within this community. If you are submitting to a top journal, make sure to prefer sources from this very journal. Try to avoid self-referencing...at least until your manuscript gets accepted ;-)

## Grammar and TeX

- Use American English (AE).
- Regarding tenses: You can either follow precicely [these](https://www.dropbox.com/s/d0s4dywiy8s25jd/A%20SHORT-CUT%20TO%20UNDERSTANDING%20TENSES_v3.doc?dl=0) rules for tenses. Or just use present tense throughout your whole paper. The decision is yours, there is nothing in between.
<p align="center">
    <img src="https://media.giphy.com/media/SQgEr5ViRcXYs/giphy.gif" alt="Yoda">
  </a><br/>
</p>

- Always use the package cleveref for cross-referencing of figues, chapters, tables, etc. with \Cref
- If you are referencing a precise figure/table/section, it is spelled in upper case, e.g. Figure 1 (use \Cref, not \cref)
- If your figure or table is on a different page than the cross-reference: Use \pageref
- The dash ('—') ('---' in LaTeX) has no spaces before or after.
- Do not use " for quotes in LaTeX, but `` and ''
- You can try to force a figure or table to a certain position by using 'htbp', e.g. \begin{figure}[htbp]
