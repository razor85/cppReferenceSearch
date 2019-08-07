# cppReferenceSearch
A search plugin for Mozilla Firefox that searches in cppreference.com

- Open Browser Console (CTRL+SHIFT+J)
  - If it doesn't show a line to type, follow https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox#Enabling_the_Browser_Toolbox
  
- Drag the cppReferenceSearch.xml to an empty Firefox tab and then copy the address bar
  - e.g.: `file:///C:/cppReferenceSearch.xml` (if your file is sitting on C:)
  
- Type the following line on Browser Console (replacing the first parameter by the address you copied on the previous step):
  - `Services.search.addEngine("file:///C:/cppReferenceSearch.xml", null, null, false);`

