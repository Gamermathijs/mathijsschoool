```
public class GekkeGlenn extends AboutMe {

public GekkeGlenn() {
    super("Gamermathij", "Netherlands");

    this.addTopLanguages("C#", "Java")
    this.addLanguage("html", "css", "javascript", "nodejs");
  }
}

public abstract class AboutMe {

  private final String name;
  private final String country;

  private ArrayList<String> topLanguages = new ArrayList<>();
  private ArrayList<String> languages = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addTopLanguages(String... topLanguages) {
    this.topLanguages.addAll(topLanguages);
  }

  public void addLanguage(String... language) {
    this.languages.addAll(language);
  }
}
```
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Gamermathijs&show_icons=true&theme=radical)
