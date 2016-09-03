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
    
   /* c. Create get and set functions for all the class properties. */	 
   
    <?php
     public function getName(){
		
		return $this->name;
	}	
		
	public function setName($name){
		
		$this->name = $name;
		
	}	
	public function getEXP(){
		
		return $this->experience;
	}
	public function setEXP($experience){
		
		$this->experience =$experience;
		
	}
	public function getLANG(){
		
		return $this->lang;
	}
	public function setLANG($lang){
		
		$this->lang =$lang;	
	}
	
	public function getEDU(){
		
		return $this->education;
	}
	public function setEDU($education){
		
		$this->experience =$education;
	
	}
	
/* e. Instantiate Programmer to the object called Paul that have the following attributes: Name = Paul Conrad Experience = 12 Language = PHP Education = Bachelor of Science in Computer Science */

        $Paul = new Programmer('Paul Conrad', 12, 'PHP', 'Bachelor of Science in Computer Science');
        
/* f. Display the programmer information using the output function. */
        $Paul->output();
        
/* g. Use the setter function to change Paul Conrad years of experience from 12 to 30 and language from PHP to Java. */

        $Paul->setEXP(30);
        $Paul->setLANG('Java');        

/* h. Display programmer updated information using the output function. */

        $Paul->output();

/* i. Use the getter function to display the programmer name and education.[2 marks] */

        echo "Programmer's Name: ".$Paul->getName().'<br>';
        echo "Education: ".$Paul->getEDU();        
        
     ?>
