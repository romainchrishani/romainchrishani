<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Romain Perera — Java Styled README</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <!-- Highlight.js CSS (GitHub-like) -->
  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.8.0/styles/github-dark.min.css">
  <style>
    body {
      background: #0b1220;
      color: #d6e3f0;
      font-family: Inter, "Segoe UI", Roboto, "Helvetica Neue", Arial, monospace;
      margin: 0;
      padding: 40px 20px;
      display: flex;
      justify-content: center;
    }

    .container {
      max-width: 900px;
      width: 100%;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius: 12px;
      padding: 28px;
      box-shadow: 0 10px 30px rgba(2,6,23,0.6);
      border: 1px solid rgba(255,255,255,0.03);
    }

    h1 {
      margin: 0 0 6px 0;
      color: #e6eef8;
      font-weight: 700;
      text-align: center;
      font-size: 24px;
    }

    h2 {
      margin: 16px 0 8px 0;
      font-weight: 600;
      color: #cfe6ff;
      text-align: center;
      font-size: 14px;
    }

    .code-block {
      margin-top: 18px;
      border-radius: 8px;
      overflow: hidden;
      border: 1px solid rgba(255,255,255,0.03);
    }

    pre {
      margin: 0;
      padding: 20px;
      overflow: auto;
      background: transparent;
    }

    /* center stats images */
    .stats {
      display: flex;
      gap: 12px;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      margin-top: 22px;
    }

    .stats img {
      border-radius: 8px;
      border: 1px solid rgba(255,255,255,0.03);
      background: rgba(255,255,255,0.02);
      box-shadow: 0 6px 18px rgba(2,6,23,0.5);
    }

    .footer {
      margin-top: 20px;
      text-align: center;
      font-style: italic;
      color: #9fb4d8;
      font-size: 13px;
    }

    a {
      color: #9fd0ff;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Romain Perera</h1>
    <h2>BSc (Hons) in Information Technology — University of Moratuwa</h2>

    <div class="code-block">
<pre><code class="language-java">/*
      (
       )     (
      ___...(-------)-....___
  .-""       Java Lover      ""-.
 .'.  '   Coding with Coffee   .'.
:  :  :    by Romain Perera    :  :  :
:  :  :..------------------..:  :  :
'. '  ' :                    : '  ' .'
  '-.___:                    :__.-'
        """---...___...---"""

*/

public class RomainPerera {

    public static void main(String[] args) {
        RomainPerera romain = new RomainPerera();
        romain.introduce();
        romain.skills();
        romain.contact();
    }

    void introduce() {
        System.out.println("Hi, I'm Romain Perera");
        System.out.println("BSc (Hons) in Information Technology | University of Moratuwa");
        System.out.println("Passionate about coding, problem-solving, and clean software design.");
    }

    void skills() {
        String[] languages = {"Java", "HTML", "CSS", "JavaScript"};
        String[] tools = {"Git", "GitHub", "VS Code"};

        System.out.println();
        System.out.println("Languages I use:");
        for (String lang : languages) {
            System.out.println("- " + lang);
        }

        System.out.println();
        System.out.println("Tools I work with:");
        for (String tool : tools) {
            System.out.println("- " + tool);
        }
    }

    void contact() {
        System.out.println();
        System.out.println("Let's connect!");
        System.out.println("GitHub: github.com/romainchrishani");
        System.out.println("Email: romainchrishani@gmail.com");
        System.out.println("LinkedIn: linkedin.com/in/romainchrishani");
    }
}

/*
  GitHub Insights (images below are live)
*/
</code></pre>
    </div>

    <div class="stats" aria-hidden="false">
      <!-- Replace username in URLs if needed -->
      <img src="https://github-readme-stats.vercel.app/api?username=romainchrishani&show_icons=true&theme=tokyonight&hide_border=true"
           alt="GitHub Stats" height="150">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=romainchrishani&layout=compact&theme=tokyonight&hide_border=true"
           alt="Top Languages" height="150">
      <img src="https://streak-stats.demolab.com?user=romainchrishani&theme=tokyonight&hide_border=true"
           alt="GitHub Streak" height="150">
    </div>

    <div class="footer">
      Code-style README — designed to look like Java source. • <a href="https://github.com/romainchrishani">github.com/romainchrishani</a>
    </div>
  </div>

  <!-- Highlight.js -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.8.0/highlight.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.8.0/languages/java.min.js"></script>
  <script>
    // initialize highlight.js
    hljs.configure({languages: ['java']});
    document.querySelectorAll('pre code').forEach((el) => hljs.highlightElement(el));
  </script>
</body>
</html>


<!---
romainchrishani/romainchrishani is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
