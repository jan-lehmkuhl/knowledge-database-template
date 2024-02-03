---
id: 488d7bbf-4807-4a12-afdb-9be85d28b850
created: 2023-12-03 22:02
keywords: 
  - #permanent-note
---


Literature Excerpts
======================================================================

One major task for a knowledge base is to incorporate statements from other resources like papers and books.  

See example [Lehmkuhl2018](/engineering/computational-fluid-dynamics/wall-functions/_resources/Lehmkuhl2018_Dissertation_modeling-a-numeric-wall-function.md) 
for [Wall Function Modeling](/engineering/computational-fluid-dynamics/wall-functions/README.md).  

I adapted this workflow/concept from [Citavi](../tools/citavi.md) which is very good at this.  



Workflow
------------------------------------------------------------

### Add a new Resource Note
1. Create a subfolder `_resources` in an appropriate category
2. Create a markdown file with the name `AuthorYEAR_shortened-title` as Resource Note  
3. Insert the [snippet](/coding/editors/vs-code/snippets.md) `literature content header` at the top of the markdown Resource Note  
4. Add if available the pdf with the same name like the Resource Note  


### Review the Literature and make Excerpts
5. Read the Paper very fast to get a glimpse of the content. 
6. Read it again and find important statements and make an excerpt in the Resource Note. 
    * Copy the text you want to cite and keep it in the clipboard
    * Insert the snippet `literature excerpt` in the Resource Note. 
      The citation text is inserted automatically 
    * Fill out the "key statement" and the optional assessment and synopsis


### Put the Excerpts into Context/Notes
7. Review every excerpt and decide if its possible to make a link in some regular notes. 
8. Go to the other regular note and make a [Markdown Link with Header](/coding/languages/markdown/links.md#links-zu-überschriften) to the Excerpt Header ID. 
   E.g. [Lehmkuhl2018 333966](/engineering/computational-fluid-dynamics/wall-functions/_resources/Lehmkuhl2018_Dissertation_modeling-a-numeric-wall-function.md#333966) 
9. Improve the regular note 
    * Recite the key statement and keep the reference as proof
    * Add more context 
    * ...



RESOURCES
======================================================================

see [Citavi](/knowledge/tools/citavi.md)  
