## Newest Tasks
- [x] Move display theme selector inside Quick Info window
- [x] Style Connect links to look like actual Win98 hyperlinks  
- [x] Make Properties window consistent size with internal scrolling
- [x] Update education to Virginia Tech with proper formatting
- [x] Add Claude mentions throughout for SEO
- [x] Update business card to match main site content

## Design Review Tasks
- [x] have graphic designer review business card
- [x] recruiter review it. make sure it's geared towards an AI event


# follow instructions here

plan the implementation first.
then evaluate and revise the plan. think.
then implement.

# todo

## New Tasks
- [x] the display properties takes so much visual attention. it needs to be like an afterthought. put it in like bottom right of the quick ifno bar or something. 
- [x] use the horizontal space for connect links. maybe like flex and make the links consistent sizes. 2x2 grid? 
- [x] I downlaoded the qr code into public, so don't use the live version

## Completed Tasks
- [x] put status bar bottom of quick info
- [x] fix social links on XP version: needs more padding at top
- [x] Add "Connect" title bar to social links window
- [x] Add education to experience 
- [x] put experience table in below container like below
```
<div class="sunken-panel" style="height: 120px; width: 240px;">
  <table class="interactive">
    <thead>
      <tr>
        <th>Name</th>
        <th>Version</th>
        <th>Company</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>MySQL ODBC 3.51 Driver</td>
        <td>3.51.11.00</td>
        <td>MySQL AB</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
      <tr>
        <td>SQL Server</td>
        <td>3.70.06.23</td>
        <td>Microsoft Corporation</td>
      </tr>
    </tbody>
  </table>
</div>
<script>
  document.querySelectorAll('table.interactive').forEach(element => {
    element.addEventListener('click', (event) => {
      const highlightedClass = 'highlighted';
      const isRow = element => element.tagName === 'TR' && element.parentElement.tagName === 'TBODY';
      const newlySelectedRow = event.composedPath().find(isRow);
      const previouslySelectedRow = Array.from(newlySelectedRow.parentElement.children).filter(isRow).find(element => element.classList.contains(highlightedClass));
      if(previouslySelectedRow){
        previouslySelectedRow.classList.toggle(highlightedClass);
      }

      if (newlySelectedRow) {
        newlySelectedRow.classList.toggle(highlightedClass);
      }
    })
  });
</script>
```

- [x] i've also had recent experience working in at SharpTax in arlington. I was automating and enhancing their workflow with custom scripts to increase usability, eg adding quick-copy buttons to important info. i want to add that in there.
- [x] for the main blurb thing, i want to use a summary that conveys "I use bleeding edge agentic software engineering techniques to make codebases build themselves". we may need to discuss this.
  - [x] change to 'me make computer do work.' makes me seem more human
  - don't use any 90s baby refernces.
- [x] make socials links stylized like actual links you'd see on windows software. maybe add a clipart glboe. like this icon can be used somewhere in the window https://win98icons.alexmeub.com/icons/png/entire_network_globe-0.png
- [x] use https://nut-prototype.pages.dev as the link to lilaya. i put a screenshot as  lilaya-screenshot in public/
- [x] business card qr code not working. also add a back button to navigate back to main site.
  - [x] adjust business card content to consistent with main site.
  - [x] add link to business card version in main site
- [x] the 60x thing seems so pushed and forced. what do you think (toned down emphasis)

