# Hugo Shortcodes

Custom shortcodes for Hugo.

* **xref**: Cross-reference to a page, which automatically gets the title of the page that you link to.  
  **Usage**: `{{< xref "foldername\filename.md" >}}`
* **conref**: Embeds the content of a page into the current page.  
  **Usage**: `{{< conref "foldername\filename.md" >}}`. _Note_: The path is relative to the `content` folder. For example, if you want to include `content/intro/groovypants/hello.md`, in the shortcode, you need `intro/groovypants/hello.md`. 
