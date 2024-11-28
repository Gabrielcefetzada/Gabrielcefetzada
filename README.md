<h1 align="center">
  ⭐⭐ Hello everyone ⭐⭐
</h1>
 
  ```php
    <?php
    class Education {
      public string $area;
      public string $institution;
      public string $degree;
      public string $status;

      public function __construct(string $area, string $degree, string $institution, string $status) {
        $this->area = $area;
        $this->institution = $institution;
        $this->degree = $degree;
        $this->status = $status;
      }
    }

    $gabriel = [
      'age' => 21,
      'location' => 'Brazil',
      'currentJob' => 'Back-End Software Developer',
      'education' => [
        new Education('Computer Network', 'Technical', 'CEFET-MG', 'Graduated'),
        new Education('Software Engineering', 'BS', 'PUC Minas', 'Enrolled')
      ]
    ];

    var_dump($gabriel);
    ?>
  ```
