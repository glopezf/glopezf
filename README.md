# Hi there 👋, my name is Gonzalo López
## My current job title is "Systems Administrator" although I feel much more identified as "Full Stack Developer and fire extinguiser professional", on my daily tasks I do:

* <img src="./resources/2BDB-FX5.svg" alt="PHP" title="PHP" style="color:#CC2927" height="20px"/> PHP coding and recoding
* <img src="./resources/InSc0e1m.svg" alt="SQL Server" title="SQL Server" style="color:#CC2927" height="20px"/> SQL Server database administration
* <img src="./resources/8n7rL6ZU.svg" alt="Algorithms" title="Algorithms" style="color:#CC2927" height="20px"/> Implementation and creation of new procedures within our current management systems
* <img src="./resources/AQ2Csr-r.svg" alt="Algorithms" title="Algorithms" style="color:#CC2927" height="20px"/> Azure administration
* <img src="./resources/b7pEII6f.svg" alt="Algorithms" title="Algorithms" style="color:#CC2927" height="20px"/> Exchange online administration
* <img src="./resources/OBLogo.svg" alt="Algorithms" title="Algorithms" style="color:#CC2927" height="20px"/> Learning and training myself constantly
* <img src="./resources/6TFBFju8.svg" alt="Algorithms" title="Algorithms" style="color:#CC2927" height="20px"/> Microsoft 365 Administration


```php

<?php
class Skill {
  // Properties
  public $name;
  public $skillLevel;
  public $experience; // years

  // Methods
  function set_name($name) {
    $this->name = $name;
  }
  function get_name() {
    return $this->name;
  }
  function set_skillLevel($skillLevel) {
    $this->skillLevel = $skillLevel;
  }
  function get_skillLevel() {
    return $this->skillLevel;
  }  
  function set_experience($experience) {
    $this->experience = $experience;
  }
  function get_experience() {
    return $this->experience." years";
  }
}

$skill1 = new Skill();
$skill1->set_name = 'PHP';
$skill1->set_skillLevel = 'expert';
$skill1->experience = 10;

$skill2 = new Skill();
$skill2->set_name = 'JavaScript';
$skill2->set_skillLevel = 'medium';
$skill2->experience = 2;

$skill3 = new Skill();
$skill3->set_name = 'jQuery';
$skill3->set_skillLevel = 'advanced';
$skill3->experience = 3;

$skill4 = new Skill();
$skill4->set_name = 'SQLServer';
$skill4->set_skillLevel = 'expert';
$skill4->experience = 10;

$skill5 = new Skill();
$skill5->set_name = 'Microsoft365Administration';
$skill5->set_skillLevel = 'advanced';
$skill5->experience = 2;

$skill6 = new Skill();
$skill6->set_name = 'AzureAdministration';
$skill6->set_skillLevel = 'medium';
$skill6->experience = 1;
?>
