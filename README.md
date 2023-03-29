# Python code change patterns

On this page, you will find code change patterns that were extracted from open source Python repositories. Each pattern consists of several instances of similar code changes. The "JSON" directory includes pattern information in `JSON` format, while the "FRAGMENTS" directory contains code changes associated with each pattern. To access code changes in the "FRAGMENTS" folder, you can use the "PATTERN_ID" and "FRAGMENT_ID" fields. The folders in "FRAGMENTS" are named according to the "PATTERN_ID," while the code change files are named after the "FRAGMENT_ID."

You can access the code change pattern in HTML format through this link (https://pycpat.github.io/HTML/2/directory.html) by using the pattern ID, which is also the name of the corresponding JSON file. Here is some information about the contents of the JSON file:
```json
{
"PATH" : "To find the HTML illustration of the pattern, you can add the prefix https://pycpat.github.io/HTML/ to this filed"  
"NODES" : "Information about the pattern's repeated nodes"
    {
      "BEFORE_CHANGE" : "Nodes belonged to the code before to the change."
      "AFTER_CHANGE" : "Nodes belonged to the code after to the change."
    }
"NUMBER_OF_REPEATED_NODES": "The number of repeated nodes in the pattern's code change instances"
"Fragments" : "Information of code changes instances"
    {
      "FRAGMENT_ID" : "A unique ID is used to identify the fragment. You can use this ID to links to the code change in the "FRAGMENT" folder."
      "PROJECT_NAME" : "The project to which the change pertains"
      "COMMIT_NAME" : "Commit hex"
      "TIME" : "The git commit time"
      "AUTHOR_NAME" : "Author of the commit"
      "FILE_NAME" : "The file in which the change is made"
      "CLASS_NAME" : "The class in which the change is made"
      "AUTHOR_NAME" : "Author email address"
      "COMMITTER_EMAIL" : "Commiter email address"
      "NODE_INFO" : "The information of the repeated nodes of the fragment"
      {
          "END_CHARACTER": "End character position of the AST nodes",
          "START_LINE_NUMBER": "Line number of the node",
          "AST_CLASS":"AST node name",
           "LENGTH": "Character length of the node",
          "START_CHARACTER":"Start character of AST node",
          "END_LINE_NUMBER": "End line number of of the node"
      }
    }
 "ID": "Pattern ID",
"PATTERN_SIZE": "Number of code changes instances of the pattern"

}

