# follow instructions here

plan the implementation first.
then evaluate and revise the plan. think.
then implement.

# todo

- [ ] put status bar bottom of quick info
- [ ] fix social links on XP version: needs more padding at top
- [ ] Add "Connect" title bar to social links window
- [ ] Add education to experience 
- [ ] put experience table in below container like below
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

- [ ] i've also had recent experience working in at SharpTax in arlington. I was automating and enhancing their workflow with custom scripts to increase usability, eg adding quick-copy buttons to important info. i want to add that in there.
- [ ] for the main blurb thing, i want to use a summary that conveys "I use bleeding edge agentic software engineering techniques to make codebases build themselves". we may need to discuss this.
  - [ ] change to 'me make computer do work.' makes me seem more human
  - don't use any 90s baby refernces.
- [ ] make socials links stylized like actual links you'd see on windows software. maybe add a clipart glboe. like this icon can be used somewhere in the window https://win98icons.alexmeub.com/icons/png/entire_network_globe-0.png
- [ ] use https://nut-prototype.pages.dev as the link to lilaya. i put a screenshot as  lilaya-screenshot in public/
- [ ] business card qr code not working. also add a back button to navigate back to main site.
  - [ ] adjust business card content to consistent with main site.
  - [ ] add link to business card version in main site
- the 60x thing seems so pushed and forced. what do you think

