# Markdown-for-Lawyers

Larry Lessig is famous for saying "Code is law."  And some lawyers have suggested that the legal and technical uses of the word "code" are similar.  

This project makes a more granular claim:  *the Law is coding*. 

## Coders > lawyers @ technical documents  

By saying "the law is coding," I mean that legal writing is like software engineering.  Lawyers produce pleadings and briefs, often working together in firms.  Those documents interact with the elements of common law and statutory law objects. They can be fabulously complex. 

Software developers do a similar thing. They produce massive projects of complex computer instructions. But those projects are, essentially, technical documents.

IT tools have seen a revolution in the last three decades. They support amazingly complex projects, and they allow fantastic amounts of collaboration.  Coding projects often have similar structures, so even neophytes can suggest imporvements.   And the skills learned in one project are often transferable to another, with little training.     

In the legal industry, our tools have stagnated: we rely on Microsoft Word where we can't rely on WordPerfect.  And even there, we're stunted;  in twelve years of practice, I've never received a document from another lawyer that used Word's style sheets correctly.     

## Legal Typetsetting Malpractice
Some of that stagnation arises out of the lawyer's duty to operate a small typesetting firm as they explain the law.  If you look at the "local rules" of many courts, you will find complex typesetting preferences set down with the force of law.  A violation of those rules carries the threat of professional malpractice.   U.S. District Judge James Bredar recently criticized parties for referring to cases in footnotes. He thought the Bluebook demanded references in the body of the brief.   “Future noncompliant filings will be stricken without prior notice." In fact, the rule cited is not nearly so firm.   But even if it was true, why should your highly paid attorney lose your case in front of Judge Bredar based on footnote placement? 

The legal industry takes some of the most expensive professional time in the world, and decrees that cases can be lost based on typesetting. So an obscene amount of time and money goes into in every major appellate argument on compliance with formatting rules.  Not grammar and syntax, but formatting.  

This typesetting layer is a bottleneck.  Try, just try, to collaborate on formal documents with a major law firm using something other than .pdfs or .docx files.  It will result in a complete breakdown; most of the criticism will be about formatting.  And until the formatting is right, the legal argument won't receive much attention at all.  

## Separating Content from Style with Markdown

In the tech world, most designers try to separate *content * and presentation.*   

That is, the wording of the document is a different discipline than making content look good.  The syntax, grammar, and structure of code matters, but it's usually stored in plain text.  This allows widespread cooperation on content.  For example, Docker, an open source software project, has nearly 1,500 contributors on GitHub.  Its software is worth a billion dollars.  It is not a cut-rate strategy to producing technical documents.  Few legal tools come close.

One of the best tools for drafting written content in technology is John Gruber's Markdown syntax.  Markdown is plain text.  But it includes structure and formatting symbols, using asterisks, hashtags, and a few others.  The writer can focus on language and minimal structure.  Software handles the formatting of that language.  This README.md file is markdown.  A separate bit of code determines how your computer displays the fonts, headings, and footnotes. 

I created this repository in 2012. I wanted to show a bit of my workflow, where I separate legal drafting from legal typesetting.  In the repo, a small .css style-sheet can take my content and turn it into a Word-editable document.  It gets close to a Missouri-compliant pleading, and reduces the amount of time I worry about format while drafting. 

We're a long way from Courts accepting xml or text filings.  But markdown is a good first step toward separating legal argument  from legal typesetting.  They're two different skills, and it's more efficient to focus on them one at a time. 

Jon Whitehead

jon@whiteheadlawllc.com

@jrwhitehead



