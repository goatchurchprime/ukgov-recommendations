## Recommendex.gov

Quality assurance by issue tracking inspired by [Francis's Github House](http://www.wired.com/2013/01/this-old-house/)

1.  The [Commons Public Accounts Committee](http://www.parliament.uk/business/committees/committees-a-z/commons-select/public-accounts-committee/publications/) has published 20 reports in this 2014-2015 session alone.  These reports (in PDF form) contain 113 Recommendations.

2.  (Unfortunately the Briefings paper dataset on http://www.data.parliament.uk/ doesn't link to these.  [NAO reports](http://www.nao.org.uk/search/type/report/) do contain recommendations, but they are too wishy-washy in the context of a database) .

3.  A "Recommendation" fits the paradigm of a bug report or [issue](https://guides.github.com/features/issues/) on the Github system.

4.  The amazing [PDF.js](http://mozilla.github.io/pdf.js/) renders the PDF files directly in the browser and allows us to build a user interface for slicing out these recommendations while maintaining a direct link back to the detailed evidence and justifications of the complete report.  

6.  The issue tracker provides the ability for people to:
    * add comments, vote on issues, and edit the description
    * apply state labels to new issues ("invalid", "duplicate", "wontfix", etc), 
    * assign an issue to a particular person to be dealt with
    * schedule issues to be finished by a particular milestone
    * close an issue once it's fixed
    * re-open an issue if is is deemed not to have actually been fixed
    
7.  Currently this workflow exists in an approximate form through grab-bag government responses to committee reports, like: [Cm 8697](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/239115/32914_Cm_8697_v0.2.pdf) "_Government responses on the First, the Third to the Fifth, the Seventh to the Twelfth, and the Fifteenth and Sixteenth Reports from the Committee of Public Accounts. Session 2013-14._"



 
NB this was hacked at the [ACCHACK14](http://hacks.rewiredstate.org/events/acchack14) and requires [twistcodewiki](https://bitbucket.org/goatchurch/twistcodewiki) to load PDFs and javascript through localhost:9003.  There are more standard ways to do this.
