# PyCPat.github.io

This page contains code change patterns that were mined from open source Python repositories. Each code change pattern consists of multiple instances of similar code changes. The "JSON" folder contains the pattern information in JSON format, while the "FRAGMENTS" folder contains the code changes that belong to each pattern.
You can use the PATTERN_ID and the FRAGMENT_ID fields to access code changes in 

Below is the Json filde infomation. 
- The Json file name is the pattern ID and you can use the pattern ID to access the pattern in html format in this link (https://pycpat.github.io/HTML/2/directory.html) for bettter illustration of the pattern.
- Json file information:
```json
{
"PATH" : "You can prefic this with https://pycpat.github.io/HTML/ to locate the html illustration of the pattern"
"NODES" : "Information of the repeated nodes of the pattern"
    {
      "BEFORE_CHANGE" : "Nodes belong to the code before the change"
      "AFTER_CHANGE" : "Nodes belong to the code after the change"
    }
"NUMBER_OF_REPEATED_NODES": "Number of repeated nodes among the code change instances of the pattern"
"Fragments" : "Information of code changes instances"
    {
      "FRAGMENT_ID" : Unique ID to identify the fragment. You can use this ID to access the code change in the "FRAGMENT" folder.
      "PROJECT_NAME" : "The project that the change is belong to"
      "COMMIT_NAME" : "Commit hex"
      "TIME" : "The git commit time"
      "AUTHOR_NAME" : "Author of the commit"
      "FILE_NAME" : "The file that the change is performed"
      "CLASS_NAME" : "The class that the change is performed"
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

