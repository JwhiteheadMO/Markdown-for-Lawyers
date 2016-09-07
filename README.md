# Markdown-for-Lawyers

Larry Lessig is famous for saying "Code is law."  And some lawyers have suggested the "United States Code" is no accident. 

This project takes a more granular:  *the Law is coding*. 

## Coders are better than lawyers at producing complex, information-heavy documents.  

By saying "the law is coding," I mean that the practice of legal writing is similar to the end-product of software engineering: sets of documents that are fabulously complex, and often the product of collaboration.  Lawyers produce pleadings and briefs, often working together in firms.  The legal content of those pleadings and briefs are interacting with common law and statutory law objects, which often have several key properties or elements.    

Software developers do a similar thing. They produce massive projects of intensely complex computer instructions, manipulating objects, to acheive a desired result.  And the tools available to coders allow even neophytes to suggest minor modifications to major software projects.   Those skills are often transferrable from project to project.   

In the last twenty years, the development of knowledge-economy collaboration tools for producing code documents has skyrocketed.  In the legal industry, tools have stagnated: we rely on Microsoft Word where we can't rely on WordPerfect.  And even there, we're stunted;  in twleve years of practice, I've never received a document from another lawyer that actually used Word's styling capabilities.     

## Legal Typetsetting Malpractice
Some of that stagnation arises out of the lawyerly duty to operate a small typesetting firm along with explaining the law.  If you look at the "local rules" of many courts, you will find complex typesetting preferences set down with the force of law.  A violation of those rules carries the implicit threat of professional malpractice by the attorney.    U.S. District Judge James Bredar of Maryland recently criticized parties for putting references to authorities in footnotes rather than in the body of the text, citing the Bluebook, an influential manual of legal citation. “Future noncompliant filings will be stricken without prior notice." In fact, the rule cited is not nearly so firm, and that many well-respected legal writers (like Bryan Garner) prefer cases in footnotes, to avoid breaking up the text. But highly paid lawyers who do not konw Judge Bredar's footnote preference can loose their client's cases.  

Today's legal profession takes some of the most expensive professionals in the world, and threatens to decide their cases on the basis of typesetting. An obscene amount of money is spent in every major appellate argument on compliance with formatting rules.  Not grammar and syntax, but formatting.  

This typesetting layer is a bottleneck collaboration.  Try, just try, to collaborate on formal documents with a major law firm using something other than .pdfs or .docx files.  It will result in a complete breakdown; most of the criticism will be about formatting.  And until the formatting is right, the legal argument won't receive much attention at all.  

## Separating Content from Style with Markdown

In information technology, most designers acknowledge that content is *separate* from *presentation.*  That is, the wording of the document is a different discipline, a different task, than making that content look good.  The syntax, grammar, and structure of code matters, but it's usually stored in plain text.  This allows widespread cooperation on content.  For example, Docker, an open source software project, has nearly 1,500 contributors on GitHub; the software has created a billion dollar implied market capitalization. 

One of the best tools for drafting written content in information technolgy is John Gruber's Markdown syntax.  Markdown is plain text.  But it includes structure and formatting symbols, using asterisks, hashtags, and other.  The writer can focus on language.  The formatting of that language is handled software.  This file is written in markdown.  The fonts, headings, spacing, etc., are controlled separately from the text. 

This project was created in 2012, to show lawyers the potential of drafting legal writing in markdown, where the typography is controlled separately.  In this case, I've created a small .css 'style-sheet' that takes my hashtags and asterisks, and turns the rough draft into an .html document that looks fairly close to a Missouri-compliant pleading that could be filed with a court.  We're a long way from Courts accepting xml or text filings, but a good first step is letting lawyers separate legal content from legal typesetting.  They're two different tools, and it's easier to focus on them one at a time. 

Jon Whitehead
jon@whiteheadlawllc.com
@jrwhitehead




