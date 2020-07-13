Revisions made to code:

1. removed css code for background image that appears at the top of the page; moved img code to html and added an *alt* tag to image with description
1. added *alt* tag to each image with description of photo
1. in left column:
    * renamed each individual class so that they all have the same name because they are almost uniform in appearance
    * in css file, deleted attributes that repeat twice and consolidated attributes to 3 separate classes (instead of 9): *.leftBoxes*, *.leftBoxes img*, *.leftBoxes h2*
    * retained *float: left* and *float: right* attributes for photos
1. in right column:
    * renamed each individual class so that they all have the same name because they are uniform in appearance
    * in css file, deleted attributes that repeat twice and consolidated attributes into 3 separate classes (instead of 9): *.rightBoxes*, *.rightboxes h3*, *.rightboxes img*
1. applied *color: #eee* to body and removed repetitive font color elements from various classes
1. applied *color: black* to footer
1. reordered css attributes to line up with html and annotated so each section is easier to find
1. replaced *div* tags to more specific tags
    * for links at the top of page, changed *div* tags to *nav* tags
    * replaced *div* tags with corresponding sections i.e. *section*, *aside*, *article*