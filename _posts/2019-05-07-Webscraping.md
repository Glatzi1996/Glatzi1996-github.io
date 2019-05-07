# So I don´t forget...

  1. open the Link to Perseus.tufts
  2. look for the XML link
  3. cracking your head over finding the correct pattern
  4. finding the pattern: all the XML Files are named after a chronological order
  5. open the source code of http://www.perseus.tufts.edu/hopper/collection?collection=Perseus:collection:RichTimes
  6. via RegEx eliminate all unnecessary things so that only the text?doc=Perseus%3atext%3a2006.05.0003 remains
  7. open the results in Atom
  8. realizing that the extraction of the links isn´t working
  9. download Sublime
  10. copy the results into Sublime
  11. via RegEx add the first part of the missing link to all the results 
  12. now that you have the correct full link, open Gitbash
  13. type in wget -i filename.txt
  14. wait...
  15. finished!
