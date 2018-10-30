# Rochester

Midterm project by Daniel Cancelmo

[Website](http://csc174.org/midterm/dcancelmo)

[Source for information](https://en.wikipedia.org/wiki/Rochester,_New_York)

## Information Architecture

### Ontology

The index page shows the user what is being described within the site, namely the city of Rochester, NY. The terminal area links to the information.

The details page contains an overview of the city including an "at a glance" area, history, economy, and education information.

Each of the sections (excluding the overview) contains 1 subsection about a particularly notable thing related to the subject (ex. University of Rochester is  subsection of Education).


### Taxonomy

The index has the site title, a form to sign-up for the newsletter, a link to the website's source for information, and a link to learn about Rochester.

In the details page there are four main headings: Overview, History, Economy, and Education.

Each heading has an aside containing pertinent information that is best presented quickly so as to not require lots of attention. Each heading (except Overview) also has a subjeading with a specfic item of note.


### Choreography

From the index page the eye follows the z pattern from the title, to the newsletter form, to the source to the link for information in the terminal area. As it is in the terminal area a user is likely to click to learn more.

From there the details page follows an F-pattern with the Rochester logo acting as bullet points for the headings and subheadings to grab attention and asides containing quick and easy to digest information. Once a reader reaches the bottom there is a prompt to signup for the newsletter that when clicked brings the user back to the top to sign-up.

The order of headings builds on previous headings. I feel knowing about the previous headings helps to udnerstand the next one. flowing from Overview to History to Economy to Education.

## Design

### Z-Pattern

The point 1 for the z pattern is the name of the site/title to clearly show users what information will be presented.

Point 2 contains the newsletter signup form because it is a call to action so it goes in a strong area. However it is not the primary purpose so it is thus not in the terminal area. 

Point 3 contains the source for the content of the site. It supports the details page that is linked next in point 4.

Point 4 contains the link to the details page because it is the primary call to action. The primary purpose of the site is to present information.


### F-Pattern

Points 1 and 2 are identical to the z pattern for the same reasons. It also creates a similair heading to the other page to tie together the site.

The content and stories are displayed using 4 headings (with 3 subheadings) on the left side of the site. Each heading has the city logo next to it, sticking out, to allow quicker scaning by singling out the headings. The right side of each section contains relevant but easily digetible (at a glance) information since the right side of f pattern cannot command attention for as long. These asides also contain headings and subheadings with the logos sticking out.

### C.R.A.P.

The index page contrasts a blue gradient background with a red color for text and text box borders and an off-white frme for the hero iamge to make each element stand out. The same style is repeated for each of the boxes. The boxes on the left left-align with each other and the hero just as the right side boxes are right-aligned in the same way. The two header boxes are top-aligned and bottom-aligned with each other, same with the bottom buttons.

The details page continues with the color contrast (except the content/stories is now black text). Each section (and subsection) header has an image of the city logo to the left acting as a bullet point to contrast witht he otherwise flat body of text. The first aside (for the Overview) contains a different format for asides. It rpesent tabular and list style information to contrast witht the rest since it is for being "at a glance". The same structure for the main part of each section is repeated with a header and paragaph(s) followed by a subheader and paragraph(s) for all but the Overview. Each one also contains a bit of information on the right. The same alignment applie for the header as it does on the index. The logos, headers, and paragraphs neatly align with themselves. Lastly, relevant but quick information is placed next to the corresponding section of the main body of the page to display proximity.


### Font choice

I selected PT Sans to be the font for the majority of the site. However any header used (h1, h2, h3) Alegreya Sans is used. I selected both the be very clean looking so both are in the sans-serif family. Alegyra Sans is clean yet appears more authoratative and grader than PT Sans thus it fits for use in headers whereas PT Sans is simple and easy to scan, making it more suitbale for the majority of text.


### CSS Architecture

I used the SMACSS architecture. All styles are stored in styles.css

The sections used are Base, Layout, and Module in that order. The other sections of SMACSS were not needed for this CSS file.

## Content

