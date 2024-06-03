<p align="center">
  <a href="mailto:arielnnogueira2@gmail.com">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=LINK-DO-SEU-EMAIL" /></a>

  <a href="https://www.linkedin.com/in/ariel-rocha-nogueira/">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=LINK-DO-SEU-LINKEDIN" /></a>
</p>  

```php
class Developer extends Person
{
    public function __construct(
        string $name = "Ariel Nogueira",
        string $birthDate = "1998-04-22",
        string $occupationArea = "Software Engineer",
        private array $stacks = ["PHP", "JavaScript", "Typescript", "C#", "Java"],
        private array $frameworks = ["Laravel", "Hyper-F", "Symfony", "Vue.js", "Nest.js", "Next.js", "Spring"],
        private array $tools = ["Docker", "Kubernetes", "Git", "New Relic", "Dynatrace", "Grafana", "Metabase"]
    ) {
        parent::__construct(
            $name,
            $birthDate,
            $occupationArea,
        );
    }
}
```
