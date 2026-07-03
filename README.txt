To change the name and url of a Paper:

1. Find the session you want to edit

Each paper session has a heading like:

html
<span class="session-name">Generative AI, Data Protection, and Sectoral Applications (1/2)</span>
You can search for that session title to quickly jump to the right spot.


2. Find the paper list inside that session

Inside the session card, look for a <ul class="paper-list"> block. For example:

html
<ul class="paper-list">
    <li><a href="#" class="paper-link">The Right Tool for the Job: On the Selection of Mitigations for GenAI Privacy Threats</a></li>
    <li><a href="#" class="paper-link">Data Sharing with Generative AI: Privacy Calculus, Trust, and Cybersecurity Behaviour in Germany from a Multilateral Security Perspective</a></li>
    <li><a href="#" class="paper-link">To Art or Not to Art: How AI Can Pivot from Shakespearean Villain to a Restorative and Structural Hero in the Creative Industries</a></li>
</ul>

3. Change the title

Replace the text between the <a> and </a> tags with your new paper title.

Example:
Change this:

html
<li><a href="#" class="paper-link">The Right Tool for the Job...</a></li>
To this:

html
<li><a href="#" class="paper-link">My New Paper Title Goes Here</a></li>
4. Change the link

Replace the href="#" attribute with your actual URL.

Example:
Change this:

html
<a href="#" class="paper-link">My New Paper Title</a>
To this:

html
<a href="https://example.com/my-paper.pdf" class="paper-link">My New Paper Title</a>
5. Save and refresh

Save your HTML file and refresh your browser — the new title and link will appear.