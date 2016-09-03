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
	
	
/* d. Create a function called output to display the programmer name, the programmer years of experience, the programmer favorite language and the type of degree obtained.*/	
	
	function output(){
		
		echo" ------------Programmer Credential--------------".'<br>';
		echo "programme name: ".$this->name.'<br>';
		echo "Years of experience: ".$this->experience.'<br>';
		echo "Favourite Language: ".$this->lang.'<br>';
		echo "Education: ".$this->education.'<br>';
		echo '<br>';
	}
	
		
	?>
