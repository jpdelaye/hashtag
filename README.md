# hashtag
Php clas that generates hashtags from a phrase with links to Instagram, Twitter or plain text
 
Requirements php >= 5.4.0

Intallation just copy the class to your classes folder

Basic Usage;

$mywords = new phrasetowords( "Any phrase to extract hashtags from");

     $mywords->get_words("twitter");  // link to Twitter hashtag
     $mywords->get_words("Instagram"); //link to Instagram hashtag
     $mywords->get_words("hashtag"); // No link just text with "#"
     $mywords->get_words("plain"); // No link just text 
     
     
working sample here: https://intelector.com/separa-palabra/
