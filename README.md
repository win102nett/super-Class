# super-Class
Creating a php class 

     <?php
  /* a. Create class properties that contain programmer's name called name, programmer years of experience called experience, the programmer favourite language called lang, and the highest degree earned called education.*/   
     
      class Programmer{
        private $name;
        private $experience;
        private $lang;
        private $education;
      }
      
 /* b. Create a primary constructor and initialize the name, experience, language and education to a value.*/	
      
      public __construct($name, $experience, $lang, $education){
      
        $this->name = "$name";
        $this->expperience ="$experience";
        $this->lang ="$language";
        $this->education = "$education";
      
     }
    ?>
